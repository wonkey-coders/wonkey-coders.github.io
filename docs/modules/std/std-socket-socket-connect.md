_[std](../../modules/std/std-module.md):[std.socket](../../modules/std/std-socket.md).[Socket](../../modules/std/std-socket-socket.md).Connect_
##### Function Connect:[Socket](../../modules/std/std-socket-socket.md)( hostname:[String](../../modules/wonkey/wonkey-types-string.md),service:[String](../../modules/wonkey/wonkey-types-string.md),type:[SocketType](../../modules/std/std-socket-sockettype.md)=SocketType.Stream,flags:[SocketFlags](../../modules/std/std-socket-socketflags.md)=Null )
Creates a connected socket.

Attempts to connect to the host at `hostname` and service at `service` and returns a new connected socket if successful.

The socket `type` should be SocketType.Stream (the default) is connecting to stream server, or SocketType.DataGram if connecting to a datagram server.

Returns null upon failure.
