_[std](../../modules/std/std-module.md):[std.collections](../../modules/std/std-collections.md).[Stack<T>](../../modules/std/std-collections-stack.md).Capacity_
##### Property Capacity:[Int](../../modules/wonkey/wonkey-types-int.md)
Gets the storage capacity of the stack.

The capacity of a stack is the number of values it can contain before memory needs to be reallocated to store more values.

If a stack's length equals its capacity, then the next Add or Insert operation will need to allocate more memory to 'grow' the stack.

You don't normally need to worry about stack capacity, but it can be useful to use [Reserve](std-collections-stack-reserve.md) to preallocate stack storage if you know in advance
how many values a stack is likely to contain, in order to prevent the overhead of excessive memory allocation.
