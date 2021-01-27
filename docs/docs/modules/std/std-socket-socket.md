_[std](../../modules/std/std-module.md):[std.socket](../../modules/std/std-socket.md).Socket_
##### Class Socket Extends [Resource](../../modules/std/std-resource-resource.md)
The Socket class.

The socket class provides a thin wrapper around native Winsock and BSD sockets.

Sockets support asynchronous programming through the use of fibers. To connect, send or receive asynchronously, simply run the relevant socket code on its own fiber. Control will be returned to the 'main' gui fiber will the operation is busy.

Sockets are ipv4/ipv6 compatible.

| Properties | |
|:---|:---|
| [Address](std-socket-socket-address.md) | The address of the socket. _(read only)_ |
| [CanReceive](std-socket-socket-canreceive.md) | The number of bytes that can be received from the socket without blocking. _(read only)_ |
| [Closed](std-socket-socket-closed.md) | True if socket has been closed. _(read only)_ |
| [Connected](std-socket-socket-connected.md) | True if socket is connected to peer. _(read only)_ |
| [PeerAddress](std-socket-socket-peeraddress.md) | The address of the socket peer. _(read only)_ |

| Methods | |
|:---|:---|
| [Accept](std-socket-socket-accept.md) | Accepts a new incoming connection on a listening socket. |
| [Close](std-socket-socket-close.md) | Closes a socket. |
| [GetOption](std-socket-socket-getoption.md) | Gets a socket option. |
| [Receive](std-socket-socket-receive.md) | Receives data on a connected socket. |
| [ReceiveFrom](std-socket-socket-receivefrom.md) |  |
| [Send](std-socket-socket-send.md) | Sends data on a connected socket. |
| [SendTo](std-socket-socket-sendto.md) |  |
| [SetOption](std-socket-socket-setoption.md) | Sets a socket option. |

| Functions | |
|:---|:---|
| [Bind](std-socket-socket-bind.md) | Creates a datagram server socket. |
| [Connect](std-socket-socket-connect.md) | Creates a connected socket. |
| [Listen](std-socket-socket-listen.md) | Creates a stream server socket and listens on it. |

| Protected methods | |
|:---|:---|
| [OnDiscard](std-socket-socket-ondiscard.md) |  |
| [OnFinalize](std-socket-socket-onfinalize.md) |  |
