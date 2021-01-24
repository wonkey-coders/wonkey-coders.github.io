# Struct

## Introduction

Structs are similar classes, but differ in several important ways:

* A struct is a 'value type', whereas a class is a 'reference type'. This means that when you assign a struct to a variable, pass a struct to a function or return a struct from a function, the entire struct is copied in the process.

* Stucts are statically typed, whereas classes are dynamically typed.

* Struct methods cannot be virtual.

* A struct cannot extend anything.

To declare a struct:

```monkey
Struct Identifier [ <GenericTypeIdents> ]
    ...Struct members...
End
```

A struct can contain const, global, field, method and function declaratins, as well as other user defined types.
