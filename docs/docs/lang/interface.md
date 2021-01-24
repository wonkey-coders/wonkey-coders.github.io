# Interface

## Introduction

To declare an interface:

```monkey
Interface Identifier [ <GenericTypeIdents> ] [ Extends Interfaces ]
    ...Interface members...
End
```

_Interfaces_ is a comma separated list of interface types.

An interface can contain consts, globals, methods, functions, properties and other user defined types.

Interface methods are always 'abstract' and cannot declare any code.

Example for using properties in an interface:

```monkey
Interface IExample

    ' Property with Setter
    Property IntProp1( a:Int )

    ' Property with Getter
    Property IntProp2:Int()

    ' Property with Setter + Getter
    Property IntProp3:Int()
    Setter( a:Int )

End
```
