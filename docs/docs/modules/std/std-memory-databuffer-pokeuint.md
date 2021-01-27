_[std](../../modules/std/std-module.md):[std.memory](../../modules/std/std-memory.md).[DataBuffer](../../modules/std/std-memory-databuffer.md).PokeUInt_
##### Method PokeUInt:Void( offset:[Int](../../modules/wonkey/wonkey-types-int.md),value:[UInt](../../modules/wonkey/wonkey-types-uint.md) )
Writes a 32 bit unsigned int to the databuffer

In debug builds, a runtime error will occur if `offset` is outside the range of the databuffer.

| Parameters |    |
|:-----------|:---|
| `offset` | offset The offset to write. |
