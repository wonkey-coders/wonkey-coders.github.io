# Variables

## Local variables

Local variables live on the stack. To declare a local variable:

`Local identifier : Type [ = Expression ]`

...or...

`Local identifier := Expression`

## Global variables

Global variables live in global memory and exist for the lifetime of the application. To declare a global variable:

`Global Identifier : Type [ = Expression ]`

...or...

`Global Identifier := Expression`

## Consts

Consts are stored in the same way as globals, but cannot be modified after they are initialized. To declare a const:

`Const Identifier : Type = Expression`

...or...

`Const Identifier := Expression`

## Examples

```monkey
Global counter:Int
Const  PI:Double = 3.5

Function Main()
    Local x:Int = 10, y:Int = 20

    Print counter
    IncCounter()
    Print counter

    Print x
    Print y
End

Function IncCounter()
    counter += 1
End
```
