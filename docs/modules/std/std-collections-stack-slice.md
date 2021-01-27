_[std](../../modules/std/std-module.md):[std.collections](../../modules/std/std-collections.md).[Stack<T>](../../modules/std/std-collections-stack.md).Slice_
##### Method Slice:[Stack](../../modules/std/std-collections-stack.md)<T>( index:[Int](../../modules/wonkey/wonkey-types-int.md) )
##### Method Slice:[Stack](../../modules/std/std-collections-stack.md)<T>( index1:[Int](../../modules/wonkey/wonkey-types-int.md),index2:[Int](../../modules/wonkey/wonkey-types-int.md) )
Returns a range of elements from the stack.

Returns a slice of the stack consisting of all elements from `index1` until `index2` or the end of the stack.

If either index is negative, then it represents an offset from the end of the stack.

Indices are clamped to the length of the stack, so Slice will never cause a runtime error.

| Parameters |    |
|:-----------|:---|
| `index1` | index1 the index of the first element (inclusive). |
| `index2` | index2 the index of the last element (exclusive). |
