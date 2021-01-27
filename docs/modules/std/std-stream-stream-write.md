_[std](../../modules/std/std-module.md):[std.stream](../../modules/std/std-stream.md).[Stream](../../modules/std/std-stream-stream.md).Write_
##### Method Write:[Int](../../modules/wonkey/wonkey-types-int.md)( buf:Void Ptr,count:[Int](../../modules/wonkey/wonkey-types-int.md) )
##### Method Write:[Int](../../modules/wonkey/wonkey-types-int.md)( data:[DataBuffer](../../modules/std/std-memory-databuffer.md),offset:[Int](../../modules/wonkey/wonkey-types-int.md),count:[Int](../../modules/wonkey/wonkey-types-int.md) )
Writes data to the stream from memory.

Writes `count` bytes of data to the stream from either a raw memory pointer or a databuffer.

Returns the number of bytes actually written

| Parameters |    |
|:-----------|:---|
| `buf` | buf A pointer to the memory to write the data from. |
| `data` | data The databuffer to write the data from. |
| `count` | count The number of bytes to write to the stream. |
