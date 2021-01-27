_[std](../../modules/std/std-module.md):[std.memory](../../modules/std/std-memory.md).[DataBuffer](../../modules/std/std-memory-databuffer.md).PokeULong_
##### Method PokeULong:Void( offset:[Int](../../modules/wonkey/wonkey-types-int.md),value:[ULong](../../modules/wonkey/wonkey-types-ulong.md) )
Writes a 64 bit unsigned long to the databuffer

In debug builds, a runtime error will occur if `offset` is outside the range of the databuffer.

| Parameters |    |
|:-----------|:---|
| `offset` | offset The offset to write. |
