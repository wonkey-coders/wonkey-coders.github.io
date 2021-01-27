_[std](../../modules/std/std-module.md):[std.stream](../../modules/std/std-stream.md).[Stream](../../modules/std/std-stream-stream.md).ReadAll_
##### Method ReadAll:[Int](../../modules/wonkey/wonkey-types-int.md)( buf:Void Ptr,count:[Int](../../modules/wonkey/wonkey-types-int.md) )
##### Method ReadAll:[Int](../../modules/wonkey/wonkey-types-int.md)( data:[DataBuffer](../../modules/std/std-memory-databuffer.md),offset:[Int](../../modules/wonkey/wonkey-types-int.md),count:[Int](../../modules/wonkey/wonkey-types-int.md) )
##### Method ReadAll:[DataBuffer](../../modules/std/std-memory-databuffer.md)( count:[Int](../../modules/wonkey/wonkey-types-int.md) )
##### Method ReadAll:[DataBuffer](../../modules/std/std-memory-databuffer.md)(  )
Reads as many bytes as possible from a stream into memory.

Continously reads data from a stream until either `count` bytes are read or the end of stream is reached.

Returns the number of bytes read or the data read.

| Parameters |    |
|:-----------|:---|
| `buf` | buf memory to read bytes into. |
| `data` | data data buffer to read bytes into. |
| `count` | count number of bytes to read. |
