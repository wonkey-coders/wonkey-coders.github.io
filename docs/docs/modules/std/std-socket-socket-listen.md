_[std](../../modules/std/std-module.md):[std.socket](../../modules/std/std-socket.md).[Socket](../../modules/std/std-socket-socket.md).Listen_
##### Function Listen:[Socket](../../modules/std/std-socket-socket.md)( service:[String](../../modules/wonkey/wonkey-types-string.md),backlog:[Int](../../modules/wonkey/wonkey-types-int.md)=32,flags:[SocketFlags](../../modules/std/std-socket-socketflags.md)=SocketFlags.Passive )
##### Function Listen:[Socket](../../modules/std/std-socket-socket.md)( hostname:[String](../../modules/wonkey/wonkey-types-string.md),service:[String](../../modules/wonkey/wonkey-types-string.md),backlog:[Int](../../modules/wonkey/wonkey-types-int.md)=128 )
Creates a stream server socket and listens on it.

Returns a new stream server socket listening at `service` if successful.

`service` can also be an integer port number.

Returns null upon failure.

(Deprecated: )
