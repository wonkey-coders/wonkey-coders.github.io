_[std](../../modules/std/std-module.md):[std.collections](../../modules/std/std-collections.md).[Deque<T>](../../modules/std/std-collections-deque.md).Capacity_
##### Property Capacity:[Int](../../modules/wonkey/wonkey-types-int.md)
Gets the storage capacity of the deque.

The capacity of a deque is the number of values it can contain before memory needs to be reallocated to store more values.

If a deque's length equals its capacity, then the next Add or Insert operation will need to allocate more memory to 'grow' the deque.

You don't normally need to worry about deque capacity, but it can be useful to [Reserve](std-collections-deque-reserve.md) deque storage if you know in advance
how many values a deque is likely to contain, in order to prevent the overhead of excessive memory allocation.
