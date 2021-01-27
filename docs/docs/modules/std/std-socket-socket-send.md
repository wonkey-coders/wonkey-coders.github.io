_[std](../../modules/std/std-module.md):[std.socket](../../modules/std/std-socket.md).[Socket](../../modules/std/std-socket-socket.md).Send_
##### Method Send:[Int](../../modules/wonkey/wonkey-types-int.md)( data:Void Ptr,size:[Int](../../modules/wonkey/wonkey-types-int.md) )
Sends data on a connected socket.

Writes `size` bytes to the socket.

Returns the number of bytes actually written.

Can return less than `size` if the socket has been closed by the peer or if an error occured.

| Parameters |    |
|:-----------|:---|
| `buf` | buf The memory buffer to write data from. |
| `size` | size The number of bytes to write to the socket. |
