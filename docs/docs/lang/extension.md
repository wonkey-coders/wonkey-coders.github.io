# Extension

## Introduction

Extensions allow you to add extra methods and functions to existing classes or structs. Fields cannot be added this way. Private members cannot be accessed by extensions.

```monkey
Struct Foo
    Field i:Int = 0
End
```

```monkey
Struct Foo Extension
    Method Increment()
        i += 1
    End
End
```
