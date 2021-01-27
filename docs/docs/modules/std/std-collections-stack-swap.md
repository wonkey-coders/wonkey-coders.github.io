_[std](../../modules/std/std-module.md):[std.collections](../../modules/std/std-collections.md).[Stack<T>](../../modules/std/std-collections-stack.md).Swap_
##### Method Swap:Void( index1:[Int](../../modules/wonkey/wonkey-types-int.md),index2:[Int](../../modules/wonkey/wonkey-types-int.md) )
##### Method Swap:Void( stack:[Stack](../../modules/std/std-collections-stack.md)<T> )
Swaps 2 elements in the stack, or 2 stacks.

This method can be used to either swap 2 elements in the stack, or 2 entire stacks.

In debug builds, a runtime error will occur if `index1` or `index2` is out of range.

Swapping entire stacks simply swaps the storage arrays and lengths of the 2 stacks, and is therefore very fast.

| Parameters |    |
|:-----------|:---|
| `index1` | index1 The index of the first element. |
| `index2` | index2 The index of the second element. |
| `stack` | stack The stack to swap with. |
