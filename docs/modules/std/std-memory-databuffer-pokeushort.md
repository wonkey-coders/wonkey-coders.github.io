_[std](../../modules/std/std-module.md):[std.memory](../../modules/std/std-memory.md).[DataBuffer](../../modules/std/std-memory-databuffer.md).PokeUShort_
##### Method PokeUShort:Void( offset:[Int](../../modules/wonkey/wonkey-types-int.md),value:[UShort](../../modules/wonkey/wonkey-types-ushort.md) )
Writes a 16 bit unsigned short to the databuffer

In debug builds, a runtime error will occur if `offset` is outside the range of the databuffer.

| Parameters |    |
|:-----------|:---|
| `offset` | offset The offset to write. |
