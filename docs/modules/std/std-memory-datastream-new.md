_[std](../../modules/std/std-module.md):[std.memory](../../modules/std/std-memory.md).[DataStream](../../modules/std/std-memory-datastream.md).New_
##### Method New:Void( buf:[DataBuffer](../../modules/std/std-memory-databuffer.md),offset:[Int](../../modules/wonkey/wonkey-types-int.md)=0 )
##### Method New:Void( buf:[DataBuffer](../../modules/std/std-memory-databuffer.md),offset:[Int](../../modules/wonkey/wonkey-types-int.md),count:[Int](../../modules/wonkey/wonkey-types-int.md) )
Creates a new datastream.

A datastream wraps a databuffer so it can be used as if it were a stream.

In debug mode, a RuntimeError will occur if `offset` or `count` are outside the range of the databuffer.

| Parameters |    |
|:-----------|:---|
| `data` | data The databuffer to wrap. |
| `offset` | offset The starting offset. |
| `count` | count The number of bytes. |
