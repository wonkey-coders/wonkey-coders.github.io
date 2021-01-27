_[std](../../modules/std/std-module.md):[std.memory](../../modules/std/std-memory.md).[DataBuffer](../../modules/std/std-memory-databuffer.md).PeekUShort_
##### Method PeekUShort:[UShort](../../modules/wonkey/wonkey-types-ushort.md)( offset:[Int](../../modules/wonkey/wonkey-types-int.md) )
Reads a 16 bit ushort from the databuffer.

In debug builds, a runtime error will occur if `offset` is outside the range of the databuffer.

| Parameters |    |
|:-----------|:---|
| `offset` | offset The offset to read. |
