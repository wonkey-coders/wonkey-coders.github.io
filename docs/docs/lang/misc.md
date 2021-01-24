# Miscellaneous

## Line breaks in code

Lines can currently only be split after ‘[‘, ‘(‘ or ‘,’ tokens.

```monkey
Local myArray:Int[] = New Int[](
    0,
    1,
    2)

Local myarray2:String[,] = New String[
    10,
    10]
```

## Print

Writes a String or a numeric value to the output console.

```monkey
Print "Hello world" ' printing a String
Print myFloat       ' printing a Float
```

## Hexadecimal numbers ($)

Hexadecimal numbers can be entered using the $ symbol

```monkey
Local i := $A0F
```

## File privacy levels

Privacy levels can be set at file scope:

* **`Public`** can be accessed from anywhere. It is the default level.

* **`Private`** can be accessed within the file only.

* **`Internal`** can be accessed from the same module only.
