_[std](../../modules/std/std-module.md):[std.collections](../../modules/std/std-collections.md).[Stack<T>](../../modules/std/std-collections-stack.md).Erase_
##### Method Erase:Void( index:[Int](../../modules/wonkey/wonkey-types-int.md) )
##### Method Erase:Void( index1:[Int](../../modules/wonkey/wonkey-types-int.md),index2:[Int](../../modules/wonkey/wonkey-types-int.md) )
Erases an element at an index in the stack.

In debug builds, a runtime error will occur if `index` is less than 0 or greater than the stack length.

if `index` is equal to the stack length, the operation has no effect.

Erases a range of elements in the stack.

If debug builds, a runtime error will occur if either index is less than 0 or greater than the stack length, or if index2 is less than index1.

The number of elements actually erased is `index2`-`index1`.

| Parameters |    |
|:-----------|:---|
| `index` | index The index of the element to erase. |
| `index1` | index1 The index of the first element to erase. |
| `index2` | index2 The index of the last+1 element to erase. |
