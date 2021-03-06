_[std](../../modules/std/std-module.md):[std.stream](../../modules/std/std-stream.md).[Stream](../../modules/std/std-stream-stream.md).Read_
##### Method Read:[Int](../../modules/wonkey/wonkey-types-int.md)( buf:Void Ptr,count:[Int](../../modules/wonkey/wonkey-types-int.md) )
##### Method Read:[Int](../../modules/wonkey/wonkey-types-int.md)( data:[DataBuffer](../../modules/std/std-memory-databuffer.md),offset:[Int](../../modules/wonkey/wonkey-types-int.md),count:[Int](../../modules/wonkey/wonkey-types-int.md) )
Reads data from the stream into memory.

Reads `count` bytes of data from the stream into either a raw memory pointer or a databuffer.

Returns the number of bytes actually read.

| Parameters |    |
|:-----------|:---|
| `buf` | buf A pointer to the memory to read the data into. |
| `data` | data The databuffer to read the data into. |
| `count` | count The number of bytes to read from the stream. |
