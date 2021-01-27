_[std](../../modules/std/std-module.md):[std.socket](../../modules/std/std-socket.md).[SocketStream](../../modules/std/std-socket-socketstream.md).Write_
##### Method Write:[Int](../../modules/wonkey/wonkey-types-int.md)( buf:Void Ptr,count:[Int](../../modules/wonkey/wonkey-types-int.md) )
##### Method Write:[Int](../../modules/wonkey/wonkey-types-int.md)( data:[DataBuffer](../../modules/std/std-memory-databuffer.md),offset:[Int](../../modules/wonkey/wonkey-types-int.md),count:[Int](../../modules/wonkey/wonkey-types-int.md) )
Writes data to the socket stream.

Writes `count` bytes to the socket.

Returns the number of bytes actually written.

Can return less than `count` if the socket has been closed by the peer or if an error occured.

| Parameters |    |
|:-----------|:---|
| `buf` | buf The memory buffer to write data from. |
| `count` | count The number of bytes to write to the socket stream. |
