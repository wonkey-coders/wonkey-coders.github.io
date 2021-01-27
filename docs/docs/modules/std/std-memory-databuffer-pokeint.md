_[std](../../modules/std/std-module.md):[std.memory](../../modules/std/std-memory.md).[DataBuffer](../../modules/std/std-memory-databuffer.md).PokeInt_
##### Method PokeInt:Void( offset:[Int](../../modules/wonkey/wonkey-types-int.md),value:[Int](../../modules/wonkey/wonkey-types-int.md) )
Writes a 32 bit int to the databuffer

In debug builds, a runtime error will occur if `offset` is outside the range of the databuffer.

| Parameters |    |
|:-----------|:---|
| `offset` | offset The offset to write. |
