# Lambda

## Introduction

## Lambda functions

To declare a lambda function:

```
Lambda [ : ReturnType ] ( Parameters )
    ...Statements...
End
```

Lambda declarations must appear within an expression, and therefore should not start on a new line.

For example:

```monkey
Local myLambda:=Lambda()
   Print "My Lambda!"
End

myLambda()
```

To pass a lambda to a function:

```monkey
SomeFunc( Lambda()
   Print "MyLambda"
End )
```

Note the closing **`)`** after the **`End`** to match the opening **`(`** after **`SomeFunc`**.
