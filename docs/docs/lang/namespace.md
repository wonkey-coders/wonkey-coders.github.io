# Namespace

## Introduction

All identifiers declared in a Wonkey program file end up inside a 'namespace'. Namespaces are hierarchical, so in addition to identifiers declared by Wonkey code, namespaces can also contain other namespaces.

## Declaring namespaces

You control which namespace the identifiers declared in a Wonkey file go with the namespace directive:

`#!monkey Namespace namespace-path`

This directive must appear at the top of the program file, before any actual declarations are made.

A namespace path is a 'dot' separated sequence of identifiers, eg:

`#!monkey wonkey.types`<br>
`#!monkey std.collections`

The 'dot' separator indicates the namespace hierarchy, eg: `#!monkey wonkey.types` is a 'child' or 'inner' namespace of `#!monkey wonkey`.

If no namespace is specified in a program file, the identifiers go into a default namespace. This is not recommended though, as the default namespace has no name - so anything inside the default namespace cannot be 'seen' by anything outside.

## Accessing namespaces

Code can access an identifier in a namespace by prefixing the identifier with the namespace path, eg:

`#!monkey Local list := New std.collections.List<Int>`

Here, `#!monkey std.collections` refers to a namespace, while `#!monkey List` is an identifier inside  the `#!monkey std.collections` namespace.

Code inside a particular namespace does not have to use a namespace prefix to find identifiers in the same namespace or in any parent namespace, although it can still do so, eg:

```monkey
Namespace testing

Function Test()
End

Function Main()
    Test()         ' works fine...
    testing.Test() ' also works...
End
```

## Using

<!--
## The Using directive
-->

To make it easier to deal with long or complex namespace paths, the using directive provides a way to add namespace 'search paths' for locating identifiers. The using directive looks like this:

`#!monkey Using namespace-path`

A program can have multiple using directives. Using directives must appear at the top of the program file before any program declarations.

Each using directive adds a namespace to a set of 'search paths' that is used to resolve any unknown identifiers in the program code, eg:

```monkey
#Import "<std>"

Using std.collections

Function Main()
    Local list := New List<Int>
End
```

Without the using directive, this program would fail to compile because the `#!monkey List` identifier cannot be found.

However, the using direct tells the compiler look for `#!monkey List` in the `#!monkey std.collections` namespace, where it is successfully located.

If you have multiple using directives and an identifier is found in more than one namespace, you will still get a compile error. In this case, you will need to 'fully qualify' the identifier by prefixing it with the correct namespace path.

Some modules declare many namespaces, and it can often be difficult to remember where everything is. To deal with this, Wonkey provides a convenient 'double dot' form of Using that will use both a namespace AND all namespaces contained in that namespace. For example:

`#!monkey Using std..`

The double dots must appear at the end of the using.

This will use the [`#!monkey std`](../../modules/std.md) namespace, and the `#!monkey std.collections`, `#!monkey std.filesystem` etc namespaces too. This works recursively, so any namespaces inside std.collections and std.filesystem are also used.

This can of course lead to more 'duplicate identifier' clashes but is none-the-less very convenient.
