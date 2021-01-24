# Function

## Global Functions

To declare a global function:

```
Function Identifier [ GenericParams ] [ : ReturnType ] ( Parameters )
    ...Statements...
End
```

_ReturnType_ defaults to **`Void`** if omitted.

_Parameters_ is a comma separated list of parameter declarations.

## Class methods

The syntax for declaring a class method is:

```
Method Identifier [ GenericParams ] [ : ReturnType ] ( Parameters ) [ Virtual | Abstract | Override | Final | Override Final ]
    ...Statements...
End
```

If a method is declared **`Virtual`** or **`Abstract`**,
 it can be overriden by methods in derived classes.
 Overriding methods must have the same return type and parameter types as the class method, and must be declared **`Override`**.

If a method is declared **`Abstract`**, no implementation may be provided (ie: no 'statements' or 'End').
 Such a method must be overriden by a method in a derived class, and also makes its
 enclosing class implictly abstract (an abstract class cannot be instantiated).

If a method is declared **`Override`** or **`Override Final`**,
 it must override a virtual method in a base class.

If a method is declared **`Final`** or **`Override Final`**, it cannot be overriden by any methods in derived classes.

By default, class methods are final.

## Function values

Wonkey supports 'first class' functions.

This means function 'values' can be stored in variables and arrays, passed to other functions and returned from functions.
