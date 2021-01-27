_[std](../../modules/std/std-module.md):[std.socket](../../modules/std/std-socket.md).[Socket](../../modules/std/std-socket-socket.md).SetOption_
##### Method SetOption:Void( opt:[String](../../modules/wonkey/wonkey-types-string.md),value:[Int](../../modules/wonkey/wonkey-types-int.md) )
Sets a socket option.

Currently, only "TCP_NODELAY" is supported, which should be 1 to enable, 0 to disable.
