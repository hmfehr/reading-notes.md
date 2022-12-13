# Socket.io

## [Web Sockets](https://en.wikipedia.org/wiki/WebSocket)

1. What is a Web Socket?
WebSocket is a computer communications protocol, providing full-duplex communication channels over a single TCP connection.

2. Describe the Web Socket request/response handshake and what happens once the connection is established.
To establish a WebSocket connection, the client sends a WebSocket handshake request, for which the server returns a WebSocket handshake response,

3. Web Sockets provide a standardized way for the server to send content to a client without first receiving a ____ from that client.
masking key

## [Socket.io Tutorial](Socket.io Tutorial)

1. What does the event handler `io.on()` do?
listens for the handshake

2. Describe some possible proof of life or proof that the code works as expected
you can console log the local host to recive the message

3. What does socket.emit() do?
it emits the data out
