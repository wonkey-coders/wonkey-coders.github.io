_[wonkey](../../modules/wonkey/wonkey-module.md):[wonkey.types](../../modules/wonkey/wonkey-types.md).[Array<T>](../../modules/wonkey/wonkey-types-array.md).CopyTo_
##### Method CopyTo:Void( dstArray:T[],srcOffset:[Int](../../modules/wonkey/wonkey-types-int.md),dstOffset:[Int](../../modules/wonkey/wonkey-types-int.md),count:[Int](../../modules/wonkey/wonkey-types-int.md) )
Copies a range of elements from this array to another.

In debug mode, a runtime error will occur if the copy is outside the range of the array.

| Parameters |    |
|:-----------|:---|
| `dstArray` | dstArray destination of the copy. |
| `srcOffset` | srcOffset First element to copy from this array. |
| `dstOffset` | dstOffset First element to copy to in destination array. |
| `count` | count Number of elements to copy. |
