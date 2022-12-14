#  Message Queues


## [Socket.io Chat Example](https://socket.io/get-started/chat/)

1. Explain to a non-technical recruiter what the Chat Example (above) does.
the server can push messages to clients. Whenever you write a chat message, the idea is that the server will get it and push it to all other connected clients.

2. What proof of life are we getting on the backend from the above app?
`{
  "name": "socket-chat-example",
  "version": "0.0.1",
  "description": "my first socket.io app",
  "dependencies": {}
}`

3. Socket.IO gives us the i0.emit() method to send an event to everyone. What flag would you use if you want to send a message to everyone except for a certain emitting socket?
If you want to send a message to everyone except for a certain emitting socket, we have the broadcast flag for emitting from that socket:


## [Rooms](https://socket.io/docs/v4/rooms)

1. What is a room and how might a room be useful?
A room is an arbitrary channel that sockets can join and leave. It can be used to broadcast events to a subset of clients:

2. How do you join a room?
You can call join to subscribe the socket to a given channel:



3. How do you leave a room?
Upon disconnection, sockets leave all the channels they were part of automatically, and no special teardown is needed on your part.
You can fetch the rooms the Socket was in by listening to the disconnecting event:
