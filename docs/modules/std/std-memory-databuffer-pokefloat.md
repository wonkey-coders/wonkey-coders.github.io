_[std](../../modules/std/std-module.md):[std.memory](../../modules/std/std-memory.md).[DataBuffer](../../modules/std/std-memory-databuffer.md).PokeFloat_
##### Method PokeFloat:Void( offset:[Int](../../modules/wonkey/wonkey-types-int.md),value:[Float](../../modules/wonkey/wonkey-types-float.md) )
Writes a 32 bit float to the databuffer

In debug builds, a runtime error will occur if `offset` is outside the range of the databuffer.

| Parameters |    |
|:-----------|:---|
| `offset` | offset The offset to write. |
