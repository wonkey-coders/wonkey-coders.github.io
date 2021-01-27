_[std](../../modules/std/std-module.md):[std.memory](../../modules/std/std-memory.md).[DataBuffer](../../modules/std/std-memory-databuffer.md).CopyTo_
##### Method CopyTo:Void( dst:[DataBuffer](../../modules/std/std-memory-databuffer.md),srcOffset:[Int](../../modules/wonkey/wonkey-types-int.md),dstOffset:[Int](../../modules/wonkey/wonkey-types-int.md),count:[Int](../../modules/wonkey/wonkey-types-int.md) )
Copies databuffer data to another databuffer.

In debug builds, a runtime error while occur if an attempt it made to copy data outside the range of either databuffer.

| Parameters |    |
|:-----------|:---|
| `dst` | dst The destination databuffer. |
| `srcOffset` | srcOffset The starting byte offset in this databuffer to copy from. |
| `dstOffset` | dstOffset The starting byte offest in the destination databuffer to copy to. |
| `count` | count The number of bytes to copy. |
