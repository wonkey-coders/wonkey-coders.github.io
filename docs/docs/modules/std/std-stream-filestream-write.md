_[std](../../modules/std/std-module.md):[std.stream](../../modules/std/std-stream.md).[FileStream](../../modules/std/std-stream-filestream.md).Write_
##### Method Write:[Int](../../modules/wonkey/wonkey-types-int.md)( buf:Void Ptr,count:[Int](../../modules/wonkey/wonkey-types-int.md) )
##### Method Write:[Int](../../modules/wonkey/wonkey-types-int.md)( data:[DataBuffer](../../modules/std/std-memory-databuffer.md),offset:[Int](../../modules/wonkey/wonkey-types-int.md),count:[Int](../../modules/wonkey/wonkey-types-int.md) )
Writes data to the filestream.

Writing past the end of the file will increase the length of a filestream.

| Parameters |    |
|:-----------|:---|
| `buf` | buf A pointer to the memory to write the data from. |
| `count` | count The number of bytes to write. |
