# Message Queues

## Socket.io Chat Example

1. Explain to a non-technical recruiter what the Chat Example (above) does.

   - The Chat Example is a simple chat application that allows users to send and receive messages in real-time using Socket.IO to establish a WebSocket connection and to send and receive events.

2. What proof of life are we getting on the backend from the above app?

   - The server-side application logs messages to the console to indicate when a client connects or disconnects, and when a message is received and broadcasted. This provides a visual indication that the backend is receiving and responding to events.

3. Socket.IO gives us the i0.emit() method to send an event to everyone. What flag would you use if you want to send a message to everyone except for a certain emitting socket?

   - `socket.broadcast.emit()`

## Rooms

1. What is a room and how might a room be useful?

   - A room is a logical channel that sockets (i.e., client or server connections) can join and leave. Rooms are useful for organizing sockets and allowing them to communicate with each other in a more structured and controlled way.

2. How do you join a room?

   - `socket.join(room)`

3. how do you leave a room?

   - `socket.leave(room)`

## Namespaces

1. What is a Namespace and what does it allow you to do?

   - A namespace is a logical boundary for sockets (i.e., client or server connections). It allows you to group sockets together and to communicate with them independently of other sockets.

2. Each namespace potentially has its own what? (hint: 3 things)

   1. Connected clients

   2. Rooms

   3. State

3. Discuss a possible use case for separate namespaces

   - A possible use case for separate namespaces in a Socket.IO application is to create separate chat rooms for different topics, allowing users to join and leave different rooms as needed and to communicate with other users within the same room.
