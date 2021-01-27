_[std](../../modules/std/std-module.md):[std.collections](../../modules/std/std-collections.md).[Stack<T>](../../modules/std/std-collections-stack.md).Insert_
##### Method Insert:Void( index:[Int](../../modules/wonkey/wonkey-types-int.md),value:T )
Inserts a value at an index in the stack.

In debug builds, a runtime error will occur if `index` is less than 0 or greater than the stack length.

If `index` is equal to the stack length, the value is added to the end of the stack.

| Parameters |    |
|:-----------|:---|
| `index` | index The index of the value to insert. |
| `value` | value The value to insert. |
