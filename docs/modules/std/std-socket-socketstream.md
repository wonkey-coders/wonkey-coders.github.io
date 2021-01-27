_[std](../../modules/std/std-module.md):[std.socket](../../modules/std/std-socket.md).SocketStream_
##### Class SocketStream Extends [Stream](../../modules/std/std-stream-stream.md)
The SocketStream class.

A socket stream provides a 'wrapper' around a socket that lets you read and write the socket as if it was a stream.

| Constructors | |
|:---|:---|
| [New](std-socket-socketstream-new.md) | Creates a new socketsteam from an existing socket. |

| Properties | |
|:---|:---|
| [Eof](std-socket-socketstream-eof.md) | True if socket has been closed. _(read only)_ |
| [Length](std-socket-socketstream-length.md) | Always -1. _(read only)_ |
| [Position](std-socket-socketstream-position.md) | Always 0. _(read only)_ |
| [Socket](std-socket-socketstream-socket.md) | The underlying socket. _(read only)_ |

| Methods | |
|:---|:---|
| [OnClose](std-socket-socketstream-onclose.md) | Closes the socket. |
| [Read](std-socket-socketstream-read.md) | Reads data from the socket stream. |
| [Seek](std-socket-socketstream-seek.md) | No operation. |
| [Write](std-socket-socketstream-write.md) | Writes data to the socket stream. |
