# Pointers

## Introduction

Pointers are special variables containing a memory address.
In Wonkey pointers are mainly used with external C/C++ code.
Try not to use pointers unless absolutely necessary. It can lead to bugs if the pointed address is not kept "alive". Pointers to globals are safe, for example.  
You must have access to the memory you're trying to reach or you'll have a (fatal) memory access violation.

A pointer should not point to a class instance. To get a pointer to your class object, you'll have to cast it to `Void Ptr`. See example below.

## Pointer declaration: Ptr

Use the **`Ptr`** keyword to declare a pointer.

```monkey
Local myPtr:Int Ptr

Local anotherPtr:Void Ptr
```

## Pointer referencing: VarPtr
 
Use the **`VarPtr`** operator to reference a pointer

```monkey
Local i:Int = 1
Local myPtr:Int Ptr

myPtr = VarPtr i
```

The *myPtr* pointer now points to the variable *i*.

## Dereferencing with []

You can access the pointed value(s) with the **`[]`** index operator

```monkey
Local i:Int = 1
Local myPtr:Int Ptr

myPtr = VarPtr i
Print myPtr[0]
```

Will print 1, the value of **`i`**.<br>

!!! warning
    You can use pointer arithmetics with the index operator **`[]`** but you have to be sure you have access to that part of the memory or you'll get a memory access violation!

## Dereferencing with ->

You can access a struct's fields, methods,.. with the **`->`** operator. It is equivalent to **`[0].`**.
 Note that creating a pointer to class is prohibited.

```monkey
Struct Str
    Field i:Int = 1
End

Function Main()
   Local s := New Str
   Local strPtr:Str Ptr

   strPtr = VarPtr s

   Print strPtr->i
End
```

will show the value of the struct's field **`i`**

## Casting

You can Cast a pointer and do some explicit conversions with the **`Cast`** operator.

`Cast<Type>(address)`

An example with a conversion from Class(reference) to Void Ptr to Class:

```monkey
Local foo := New myFooClass()
Local myVoidPtr:Void Ptr

myVoidPtr = Cast<Void Ptr>(foo)

Local foo2:myFooClass

foo2 = Cast<myFooClass>(myVoidPtr)
```

"foo" and "foo2" will have the same address(reference). Note that casting to **`Void Ptr`** is commonly used when dealing with external native code.
