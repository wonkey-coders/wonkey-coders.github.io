# Method

## Introduction

To declare a method:

```
Method Identifier [ <GenericTypeIdents> ] [ : ReturnType ] ( Arguments ) [ Modifiers ]
    ...Statements...
End
```

_ReturnType_ defaults to `Void` if omitted.

_Arguments_ is a comma separated list of parameter declarations.

_Modifiers_ can only be used with class methods, and can be one of:

* **`Abstract`** - method is abstract and has no statements block or **`End`** terminator. Any class with an abstract method is implicitly abstract.
* **`Virtual`** - method is virtual and can be dynamically overridden by a subclass method.
* **`Override`** - method is virtual and overrides a super class or interface method.
* **`Override Final`** - method is virtual, overrides a super class or interace method and cannot be overridden by subclasses.
* **`Final`** - method is non-virtual and cannot be overridden by a subclass method.  

Methods are **`Final`** by default.
