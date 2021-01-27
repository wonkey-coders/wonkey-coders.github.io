_[std](../../modules/std/std-module.md):[std.socket](../../modules/std/std-socket.md).[SocketStream](../../modules/std/std-socket-socketstream.md).Read_
##### Method Read:[Int](../../modules/wonkey/wonkey-types-int.md)( buf:Void Ptr,count:[Int](../../modules/wonkey/wonkey-types-int.md) )
##### Method Read:[Int](../../modules/wonkey/wonkey-types-int.md)( data:[DataBuffer](../../modules/std/std-memory-databuffer.md),offset:[Int](../../modules/wonkey/wonkey-types-int.md),count:[Int](../../modules/wonkey/wonkey-types-int.md) )
Reads data from the socket stream.

Reads at most `count` bytes from the socket.

Returns 0 if the socket has been closed by the peer.

Can return less than `count`, in which case you may have to read again if you know there's more data coming.

| Parameters |    |
|:-----------|:---|
| `buf` | buf The memory buffer to read data into. |
| `count` | count The number of bytes to read from the socket stream. |
