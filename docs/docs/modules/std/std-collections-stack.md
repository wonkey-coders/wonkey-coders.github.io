_[std](../../modules/std/std-module.md):[std.collections](../../modules/std/std-collections.md).Stack<T>_
##### Class Stack<T> Implements [IContainer](../../modules/std/std-collections-icontainer.md)<T>
The Stack class provides suport for dynamic arrays.

A stack is an 'array like' container that grows dynamically as necessary.

It is very cheap to add values to the end of a stack, but insertion or removal of values requires higher indexed values to be 'shifted' up or down so is slower.

Stacks implement the [IContainer](std-collections-icontainer.md) interface so can be used with Eachin loops.

| Structs | |
|:---|:---|
| [BackwardsIterator](std-collections-stack<t?>-backwardsiterator.md) | The Stack.BackwardsIterator struct. |
| [Iterator](std-collections-stack<t?>-iterator.md) | The Stack.Iterator struct. |

| Constructors | |
|:---|:---|
| [New](std-collections-stack<t?>-new.md) | Creates a new stack. |

| Properties | |
|:---|:---|
| [Capacity](std-collections-stack<t?>-capacity.md) | Gets the storage capacity of the stack. _(read only)_ |
| [Data](std-collections-stack<t?>-data.md) | Gets the underlying array used by the stack. _(read only)_ |
| [Empty](std-collections-stack<t?>-empty.md) | Checks if the stack is empty. _(read only)_ |
| [Length](std-collections-stack<t?>-length.md) | Gets the number of values in the stack. _(read only)_ |
| [Top](std-collections-stack<t?>-top.md) | Gets the top element of the stack _(read only)_ |

| Methods | |
|:---|:---|
| [Add](std-collections-stack<t?>-add.md) | Adds a value to the end of the stack. |
| [AddAll](std-collections-stack<t?>-addall.md) | Adds the values in an array or container to the end of the stack. |
| [All](std-collections-stack<t?>-all.md) | Gets an iterator for visiting stack values. |
| [Append](std-collections-stack<t?>-append.md) | (Deprecated: Use [AddAll](std-collections-addall.md).) |
| [Backwards](std-collections-stack<t?>-backwards.md) | Gets an iterator for visiting stack values in reverse order. |
| [Clear](std-collections-stack<t?>-clear.md) | Clears the stack. |
| [Compact](std-collections-stack<t?>-compact.md) | Compacts the stack |
| [Contains](std-collections-stack<t?>-contains.md) | Checks if the stack contains a value. |
| [Erase](std-collections-stack<t?>-erase.md) | Erases an element at an index in the stack. |
| [FindIndex](std-collections-stack<t?>-findindex.md) | Finds the index of the first matching value in the stack. |
| [FindLastIndex](std-collections-stack<t?>-findlastindex.md) | Finds the index of the last matching value in the stack. |
| [Get](std-collections-stack<t?>-get.md) | Gets the value of a stack element. |
| [Insert](std-collections-stack<t?>-insert.md) | Inserts a value at an index in the stack. |
| [Join](std-collections-stack<t?>-join.md) | Joins the values in a string stack. |
| [Pop](std-collections-stack<t?>-pop.md) | Pops the top element off the stack and returns it. |
| [Push](std-collections-stack<t?>-push.md) | Pushes a value on the stack. |
| [Remove](std-collections-stack<t?>-remove.md) | Finds and removes the first matching value from the stack. |
| [RemoveEach](std-collections-stack<t?>-removeeach.md) | Finds and removes each matching value from the stack. |
| [RemoveIf](std-collections-stack<t?>-removeif.md) | Removes all values int the stack that fulfill a condition. |
| [RemoveLast](std-collections-stack<t?>-removelast.md) | Finds and removes the last matching value from the stack. |
| [Reserve](std-collections-stack<t?>-reserve.md) | Reserves stack storage capacity. |
| [Resize](std-collections-stack<t?>-resize.md) | Resizes the stack. |
| [Set](std-collections-stack<t?>-set.md) | Sets the value of a stack element. |
| [Slice](std-collections-stack<t?>-slice.md) | Returns a range of elements from the stack. |
| [Sort](std-collections-stack<t?>-sort.md) | Sorts the stack. |
| [Swap](std-collections-stack<t?>-swap.md) | Swaps 2 elements in the stack, or 2 stacks. |
| [ToArray](std-collections-stack<t?>-toarray.md) | Converts the stack to an array. |
| [Operator []](std-collections-stack<t?>-opidx.md) | Gets the value of a stack element. |
| [Operator []=](std-collections-stack<t?>-opidxeq.md) | Sets the value of a stack element. |
