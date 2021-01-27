_[std](../../modules/std/std-module.md):[std.collections](../../modules/std/std-collections.md).[Stack<T>](../../modules/std/std-collections-stack.md).FindLastIndex_
##### Method FindLastIndex:[Int](../../modules/wonkey/wonkey-types-int.md)( value:T,start:[Int](../../modules/wonkey/wonkey-types-int.md)=0 )
Finds the index of the last matching value in the stack.

In debug builds, a runtime error will occur if `start` is less than 0 or greater than the length of the stack.

| Parameters |    |
|:-----------|:---|
| `value` | value The value to find. |
| `start` | start The starting index for the search. |
