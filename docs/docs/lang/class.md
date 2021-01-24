# Class

## Introduction

A class is a kind of 'blueprint' for creating objects at runtime.

The syntax for declaring a class is:

```monkey
Class Identifier [ <GenericTypeIdents> ] [ Extends SuperClass ] [ Implements Interfaces ] [ Modifier ]
    ...Class Members...
End
```

_SuperClass_ defaults to **`Object`** if omitted.

_Interfaces_ is a comma separated list of interface types.

_Modifier_ can be one of:

* **`Abstract`** - class cannot be instantiated with 'New', it must be extended.
* **`Final`** - class cannot be extended.

Classes can contain const, global, field, method and function declarations, as well as other user defined types.

Once you have declared a class, you can create objects (or 'instances') of that class at runtime using the **`New`** operator.

Classes are 'reference types', meaning that class instances are really just a 'handle' or 'pointer' to the actual class data.
