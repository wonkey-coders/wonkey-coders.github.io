_[std](../../modules/std/std-module.md):[std.collections](../../modules/std/std-collections.md).[Deque<T>](../../modules/std/std-collections-deque.md).Reserve_
##### Method Reserve:Void( capacity:[Int](../../modules/wonkey/wonkey-types-int.md) )
Reserves deque storage capacity.

The capacity of a deque is the number of values it can contain before memory needs to be reallocated to store more values.

If a deque's length equals its capacity, then the next Add, Insert or Push operation will need to allocate more memory to 'grow' the deque.

You don't normally need to worry about deque capacity, but it can be useful to use [Reserve](std-collections-deque-reserve.md) to preallocate deque storage if you know in advance how many values a deque is likely to contain, in order to prevent excessive memory allocation.

| Parameters |    |
|:-----------|:---|
| `capacity` | capacity The new capacity. |
