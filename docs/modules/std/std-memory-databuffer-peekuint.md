_[std](../../modules/std/std-module.md):[std.memory](../../modules/std/std-memory.md).[DataBuffer](../../modules/std/std-memory-databuffer.md).PeekUInt_
##### Method PeekUInt:[UInt](../../modules/wonkey/wonkey-types-uint.md)( offset:[Int](../../modules/wonkey/wonkey-types-int.md) )
Reads a 32 bit uint from the databuffer.

In debug builds, a runtime error will occur if `offset` is outside the range of the databuffer.

| Parameters |    |
|:-----------|:---|
| `offset` | offset The offset to read. |
