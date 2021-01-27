_[std](../../modules/std/std-module.md):[std.memory](../../modules/std/std-memory.md).[DataBuffer](../../modules/std/std-memory-databuffer.md).PokeByte_
##### Method PokeByte:Void( offset:[Int](../../modules/wonkey/wonkey-types-int.md),value:[Byte](../../modules/wonkey/wonkey-types-byte.md) )
Writes a byte to the databuffer.

In debug builds, a runtime error will occur if `offset` is outside the range of the databuffer.

| Parameters |    |
|:-----------|:---|
| `offset` | offset The offset to write. |
