_[std](../../modules/std/std-module.md):[std.process](../../modules/std/std-process.md).[ProcessStream](../../modules/std/std-process-processstream.md).Write_
##### Method Write:[Int](../../modules/wonkey/wonkey-types-int.md)( buf:Void Ptr,count:[Int](../../modules/wonkey/wonkey-types-int.md) )
##### Method Write:[Int](../../modules/wonkey/wonkey-types-int.md)( data:[DataBuffer](../../modules/std/std-memory-databuffer.md),offset:[Int](../../modules/wonkey/wonkey-types-int.md),count:[Int](../../modules/wonkey/wonkey-types-int.md) )
Writes data to process stdin.

Writes `count` bytes to the process.

Returns the number of bytes actually written.

Can return less than `count` if the process has ended.

| Parameters |    |
|:-----------|:---|
| `buf` | buf The memory buffer to read data from. |
| `count` | count The number of bytes to write to the process. |
