_[std](../../modules/std/std-module.md):[std.memory](../../modules/std/std-memory.md).[DataBuffer](../../modules/std/std-memory-databuffer.md).PeekString_
##### Method PeekString:[String](../../modules/wonkey/wonkey-types-string.md)( offset:[Int](../../modules/wonkey/wonkey-types-int.md) )
##### Method PeekString:[String](../../modules/wonkey/wonkey-types-string.md)( offset:[Int](../../modules/wonkey/wonkey-types-int.md),count:[Int](../../modules/wonkey/wonkey-types-int.md) )
Reads a string from the databuffer.

If `count` is omitted, all bytes from `offset` until the end of the data buffer are read.

| Parameters |    |
|:-----------|:---|
| `offset` | offset Byte offset to read the string. |
| `count` | count Number of bytes to read. |
