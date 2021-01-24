# Encapsulation

## Introduction

There are three levels of encapsulation for class and struct members:

* **`Public`** members can be accessed from anywhere. It is the default encapsulation level.

* **`Protected`** members can only be accessed by the base class and the derived ones or by class/struct extensions. Code existing in the same source file have acces to **`Protected`** members too.

* **`Private`** members can only be accessed by the base class. Code existing in the same source file have acces to **`Private`** members too.

There is also the **`Internal`** privacy level, used to declare module internal accessibility.

Example:

```monkey
Class Foo
    ' public by default
    Field i:Int

    Protected

    Field someProtectedThing:Int

    Method doSomething()
        Print "Doing something"
    End

    Private

    Field _somePrivateThing:String
End
```
