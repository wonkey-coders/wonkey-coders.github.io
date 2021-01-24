# Conversion Operators

## Introduction

You can also add 'conversion operators' to classes and structs. These allow you to convert from a custom class or struct type to an unrelated type, such as another class or struct type, or a primitive type such as String.

The syntax for declaring a conversion operator is:

```monkey
Operator To [ <GenericTypeIdents> ] : Type ()
    ...Statements...
End
```

Conversion operators cannot be used to convert a class type to a base class type, or from any type to bool.

For example, we can add a string conversion operator to a class like this:

```monkey
Struct Vec2

    Field x:Float
    Field y:Float

    Method New( x:Float,y:Float )
        Self.x=x
        Self.y=y
    End

    Method ToString:String()
        Return "Vec2("+x+","+y+")"
    End

    ' The string conversion operator
    Operator To:String()
        Return "Vec2("+x+","+y+")"
    End
End
```

This will allow Vec2 values to be implictly converted to strings where possible, for example:

```monkey
Local v:=New Vec2

Print v
```

We no longer need to use '.ToString()' when printing the string. Since Print() takes a string argument, and Vec2 has a conversion operator that returns a string, the conversion operator is automatically called for you.
