_[std](../../modules/std/std-module.md):[std.collections](../../modules/std/std-collections.md).Deque<T>_
##### Class Deque<T> Implements [IContainer](../../modules/std/std-collections-icontainer.md)<T>
The Deque class.

A deque is a 'double ended queue' (usually pronounced 'deck').

You can efficiently add items to either end of a deque using [AddFirst](std-collections-addfirst.md) and [AddLast](std-collections-addlast.md), and remove items using [RemoveFirst](std-collections-removefirst.md) and [RemoveLast](std-collections-removelast.md).

Deques implement the [IContainer](std-collections-icontainer.md) interface so can be used with Eachin loops.

Note that you should NOT modify a deque while iterating through it with an eachin loop. Doing so while cause a 'concurrent deque modification' runtime error in debug mode. Please see [IContainer](std-collections-icontainer.md) for more information.

| Structs | |
|:---|:---|
| [Iterator](std-collections-deque<t?>-iterator.md) | The Deque.Iterator struct. |

| Constructors | |
|:---|:---|
| [New](std-collections-deque<t?>-new.md) | Creates a new deque. |

| Properties | |
|:---|:---|
| [Capacity](std-collections-deque<t?>-capacity.md) | Gets the storage capacity of the deque. _(read only)_ |
| [Data](std-collections-deque<t?>-data.md) | Gets the underlying array used by the deque. _(read only)_ |
| [Empty](std-collections-deque<t?>-empty.md) | True if deque is empty. _(read only)_ |
| [Length](std-collections-deque<t?>-length.md) | Gets the number of values in the deque. _(read only)_ |

| Methods | |
|:---|:---|
| [AddFirst](std-collections-deque<t?>-addfirst.md) | Adds a value at the start of the deque. |
| [AddLast](std-collections-deque<t?>-addlast.md) | Adds a value at the end of the deque. |
| [All](std-collections-deque<t?>-all.md) | Gets an iterator for visiting deque values. |
| [Clear](std-collections-deque<t?>-clear.md) | Clears the deque. |
| [First](std-collections-deque<t?>-first.md) | Returns the first value in the deque. |
| [Get](std-collections-deque<t?>-get.md) |  |
| [Last](std-collections-deque<t?>-last.md) | Returns the last value in the deque. |
| [PopFirst](std-collections-deque<t?>-popfirst.md) | (Deprecated: use [RemoveFirst](std-collections-removefirst.md).) |
| [PopLast](std-collections-deque<t?>-poplast.md) | (Deprecated: use [RemoveLast](std-collections-removelast.md).) |
| [PushFirst](std-collections-deque<t?>-pushfirst.md) | (Deprecated: Use [AddFirst](std-collections-addfirst.md)) |
| [PushLast](std-collections-deque<t?>-pushlast.md) | (Deprecated: Use [AddLast](std-collections-addlast.md)) |
| [RemoveFirst](std-collections-deque<t?>-removefirst.md) | Removes and returns the first value in a deque. |
| [RemoveLast](std-collections-deque<t?>-removelast.md) | Removes and returns the last value in a deque. |
| [Reserve](std-collections-deque<t?>-reserve.md) | Reserves deque storage capacity. |
| [Set](std-collections-deque<t?>-set.md) |  |
| [ToArray](std-collections-deque<t?>-toarray.md) | Converts the deque to an array. |
| [Operator []](std-collections-deque<t?>-opidx.md) |  |
| [Operator []=](std-collections-deque<t?>-opidxeq.md) |  |
