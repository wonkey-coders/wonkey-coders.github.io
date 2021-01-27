_[std](../../modules/std/std-module.md):[std.memory](../../modules/std/std-memory.md).[DataBuffer](../../modules/std/std-memory-databuffer.md).PokeUByte_
##### Method PokeUByte:Void( offset:[Int](../../modules/wonkey/wonkey-types-int.md),value:[UByte](../../modules/wonkey/wonkey-types-ubyte.md) )
Writes an unsigned byte to the databuffer.

In debug builds, a runtime error will occur if `offset` is outside the range of the databuffer.

| Parameters |    |
|:-----------|:---|
| `offset` | offset The offset to write. |
