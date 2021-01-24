# String

## Introduction

A String is an immutable sequence of 16 bit characters that is usually used to represent text.

String literals are sequences of characters enclosed in `"` (quotation marks / doublequote).

String literals may also include escape sequences, special sequences of characters used to represent unprintable characters.

## Escape characters

You can use the following escape sequences in string literals:

| Escape sequence | Character code
|:----------------|:--------------
| ~q              | 34 (quotation mark ")
| ~n              | 10 (newline)
| ~r              | 13 (return)
| ~t              | 9 (tab)
| ~z              | 0 (null)
| ~~              | 126 (tilde ~)

For example, to include literal quotation marks in a string:

```monkey
Local test := "~qHello World~q"
```

Strings can also be declared across multiple lines:

```monkey
Const multiLine := "
Multi Line String
"
```

In this case, each newline inside the quote marks is simply included in the string, so the above example string actually contains 2 'hidden' newlines.

String variables are declared using the type name **`String`**, for example:

```monkey
Local test:String = "Hello World"
```

You can index a string using the **`[]`** operator:

```monkey
Local str := "Hello World"

For Local i := 0 Until str.Length
    Print str[i]
Next
```

Indexing a string will return the character code at a given string index as an int.

You can iterate through the characters in a string using **`Eachin`**:

```monkey
For Local chr := Eachin "Hello World"
    Print chr
Next
```

<!--
Strings have a number of useful methods including [[types.String.Slice|Slice]], [[types.String.Find|Find]] and [[types.String.Split|Split]]. For more information on strings, please see the [[types.String|String]] API reference.
-->
