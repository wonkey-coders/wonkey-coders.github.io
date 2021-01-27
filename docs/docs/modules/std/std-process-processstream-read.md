_[std](../../modules/std/std-module.md):[std.process](../../modules/std/std-process.md).[ProcessStream](../../modules/std/std-process-processstream.md).Read_
##### Method Read:[Int](../../modules/wonkey/wonkey-types-int.md)( buf:Void Ptr,count:[Int](../../modules/wonkey/wonkey-types-int.md) )
##### Method Read:[Int](../../modules/wonkey/wonkey-types-int.md)( data:[DataBuffer](../../modules/std/std-memory-databuffer.md),offset:[Int](../../modules/wonkey/wonkey-types-int.md),count:[Int](../../modules/wonkey/wonkey-types-int.md) )
Reads data from process stdout.

Reads at most `count` bytes from the process.

Returns 0 if the process has ended.

Can return less than `count`, in which case you may have to read again if you know there's more data coming.

| Parameters |    |
|:-----------|:---|
| `buf` | buf The memory buffer to read data into. |
| `count` | count The number of bytes to read from the process. |
