_[std](../../modules/std/std-module.md):[std.socket](../../modules/std/std-socket.md).[Socket](../../modules/std/std-socket-socket.md).Receive_
##### Method Receive:[Int](../../modules/wonkey/wonkey-types-int.md)( data:Void Ptr,size:[Int](../../modules/wonkey/wonkey-types-int.md) )
Receives data on a connected socket.

Reads at most `size` bytes from the socket.

Returns 0 if the socket has been closed by the peer.

Can return less than `size`, in which case you may have to read again if you know there's more data coming.

| Parameters |    |
|:-----------|:---|
| `buf` | buf The memory buffer to read data into. |
| `size` | size The number of bytes to read from the socket. |
