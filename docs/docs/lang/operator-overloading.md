# Operator overloading

## Introduction

Operator overloading allows you to customize the behavior of the built-in Wonkey operators for classes and structs.

You overload an operator by writing an 'operator method', which is effectively just a special kind of method. Operators must appear inside classes/structs - they cannot currently be 'global'.

Here is a simple example:
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

    ' Overload the addition operator.
    Operator+:Vec2( rhs:Vec2 )
        Return New Vec2( x+rhs.x,y+rhs.y )
    End

End
```

The **'Operator+'** declaration here defines an addition operator for Vec2. This is then used whenever a Vec2 appears as the 'left hand side' of an addition. For example:
```monkey
Function Main()
    Local v1 := New Vec2( 10.0,20.0 )
    Local v2 := New Vec2( 30.0,40.0 )
    Local v3 := v1 + v2 ' note: calls Operator+ in Vec2.
    Print v3.ToString()
End
```

The following unary operators can be overloaded: **`+`** **`-`** **`~`**

The following binary operators can be overloaded:
 **`*`** **`/`** **`Mod`** **`+`** **`-`** **`Shl`** **`Shr`** **`&`** **`|`** **`~`** **`=`** **`<>`** **`<`** **`>`** **`<=`** **`>=`** **`<=>`**

The following assignment operators can be overloaded:
 **`*=`** **`/=`** **`Mod=`** **`+=`** **`-=`** **`Shl=`** **`Shr=`** **`&=`** **`|=`** **`~=`**

Indexing behaviour can also be overloaded using **`[]`** and **`[]=`**

Note that you cannot overload **`Not`**, **`And`**, **`Or`** or plain assignment **`=`**

Operators can return any type of value, and can take any type of value for their 'right hand side' argument(s).
 However, the precedence of operators cannot be changed.

The **`[]`** and **`[]=`** operators allow you to define 'indexing' like behaviour.
 The **`[]`** operator is used when an object is indexed, and **`[]=`** is used when an object is indexed and assigned.
 Both of these operators can accept any number of parameters of any type.
 The **`[]=`** operator requires an additional parameter that is the value to be assigned.
 This must appear at the end of the parameter list.

Here is an example of some indexing operators for the Vec2 class above:

```monkey
Struct Vec2

    ...as above...

    Operator[]:Float( index:Int )
        Assert( index=0 Or index=1 )
        If index=0 Return x Else Return y
    End

    Operator[]=( index:Int,value:Float )
        Assert( index=0 Or index=1 )
        If index=0 Then x=value Else y=value
    End
End
```

With these additions, you can access Vec2 coordinates 'by index', eg:

```monkey
Function Main()
    Local v := New Vec2
    v[0] = 10.0
    v[1] = 20.0
    Print v[0]
    Print v[1]
End
```

You can also overload assignment operators, for example:

```monkey
Struct Vec2

    ...as above...

    Operator+=( v:Vec2 )
        x += v.x
        y += v.y
    End
End
```

If you have already written an Operator+ (as is the case here) this is not strictly necessary,
 as Wonkey will generate the code for Operator+= for you.
 However, you may still want to provide a custom version for Operator+= if your code can do so in a more efficient way.
