_[std](../../modules/std/std-module.md):[std.socket](../../modules/std/std-socket.md).[Socket](../../modules/std/std-socket-socket.md).Bind_
##### Function Bind:[Socket](../../modules/std/std-socket-socket.md)( service:[String](../../modules/wonkey/wonkey-types-string.md),flags:[SocketFlags](../../modules/std/std-socket-socketflags.md)=SocketFlags.Passive )
##### Function Bind:[Socket](../../modules/std/std-socket-socket.md)( hostname:[String](../../modules/wonkey/wonkey-types-string.md),service:[String](../../modules/wonkey/wonkey-types-string.md) )
Creates a datagram server socket.

Returns a new datagram server socket bound to 'service' if successful.

`service` can also be an integer port number.

Returns null upon failure.

(Deprecated: )
