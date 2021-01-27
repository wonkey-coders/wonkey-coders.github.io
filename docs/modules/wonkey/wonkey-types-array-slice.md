_[wonkey](../../modules/wonkey/wonkey-module.md):[wonkey.types](../../modules/wonkey/wonkey-types.md).[Array<T>](../../modules/wonkey/wonkey-types-array.md).Slice_
##### Method Slice:T[]( from:[Int](../../modules/wonkey/wonkey-types-int.md) )
##### Method Slice:T[]( from:[Int](../../modules/wonkey/wonkey-types-int.md),term:[Int](../../modules/wonkey/wonkey-types-int.md) )
Extracts a subarray from the array.

Returns an array consisting of all elements from `from` until (but not including) `tail`, or until the end of the string if `tail` is not specified.

If either `from` or `tail` is negative, it represents an offset from the end of the array.

| Parameters |    |
|:-----------|:---|
| ``from`` | `from` The starting index. |
| ``tail`` | `tail` The ending index. |
