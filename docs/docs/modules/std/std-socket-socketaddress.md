_[std](../../modules/std/std-module.md):[std.socket](../../modules/std/std-socket.md).SocketAddress_
##### Class SocketAddress
The SocketAddress class.

A socket address encapsulates the hostname and service of a socket.

Socket address objects are returned by the [Socket.Address](std-socket-socket.address.md) and [Socket.PeerAddress](std-socket-socket.peeraddress.md) properties, and indirectly returned by [Socket.ReceiveFrom](std-socket-socket.receivefrom.md).

| Constructors | |
|:---|:---|
| [New](std-socket-socketaddress-new.md) | Creates a new empty socket address. |

| Properties | |
|:---|:---|
| [Host](std-socket-socketaddress-host.md) | The hostname represented by the address. _(read only)_ |
| [Service](std-socket-socketaddress-service.md) | The service represented by the address. _(read only)_ |

| Methods | |
|:---|:---|
| [Operator <=>](std-socket-socketaddress-opcmp.md) | Comparison operator. |
| [To](std-socket-socketaddress-to.md) | Converts the address to a string. |
