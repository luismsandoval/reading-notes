# Socket.io

## Web Sockets

1. What is a Web Socket?

   - A WebSocket is a protocol that allows for full-duplex, bi-directional communication between a client and a server over a single TCP connection.

2. Describe the Web Socket request/response handshake and what happens once the connection is established.

   - The WebSocket handshake is the process of establishing a connection between a client and a server using the WebSocket protocol. The client sends an HTTP request with an "Upgrade" header to the server, and if the server supports WebSockets and is willing to upgrade the connection, it sends back an HTTP response with a "101 Switching Protocols" status code and an "Upgrade" header. The connection is then established and both the client and the server can send and receive data over the WebSocket connection in the form of binary frames. The connection remains open until one of the parties closes it or the connection is lost.

3. Web Sockets provide a standardized way for the server to send content to a client without first receiving a \_\_\_\_ from that client.

   - _request_

## Socket.io Tutorial

1. What does the event handler io.on() do?

   - The io.on() event handler is a method in the Socket.IO library that allows you to listen for and handle events that are emitted by the Socket.IO server or client. It takes two arguments: the name of the event and a callback function that will be executed when the event is emitted.

2. What does socket.emit() do?

   - socket.emit() is a method in the Socket.IO library that allows you to send an event from the client to the server or from the server to the client. It takes two arguments: the name of the event and the data to be transmitted with the event.

## Socket.io vs Web Sockets

1. What is the difference between WebSocket and Socket.IO? (think Git and GitHub, or OAuth and Auth0).

   - WebSocket is a protocol for full-duplex communication between a client and server, while Socket.IO is a JavaScript library that uses WebSocket as the underlying transport mechanism and provides additional features and functionality for building real-time applications. Socket.IO also has fallbacks for older browsers that do not support WebSockets.

2. When would you use Socket.IO?

   - You would use Socket.IO when you want to build real-time, interactive applications that require bi-directional communication between a client and a server, such as chat, multiplayer games, and more.

3. When would you use WebSockets?

   - You would use WebSockets when you want to build real-time, interactive applications that require bi-directional communication between a client and a server over a single TCP connection, and you do not need the additional features and functionality provided by Socket.IO.
