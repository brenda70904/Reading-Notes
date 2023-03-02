
## [Socket.io Chat Example](https://socket.io/get-started/chat/)

### Explain to a non-technical recruiter what the Chat Example (above) does.
The main idea behind Socket.IO is that you can send and receive any events you want, with any data you want

### What proof of life are we getting on the backend from the above app?
`console.log`

### Socket.IO gives us the i0.emit() method to send an event to everyone. What flag would you use if you want to send a message to everyone except for a certain emitting socket?
Use broadcast method

## [Rooms](https://socket.io/docs/v4/rooms)

### What is a room and how might a room be useful?
A room is an arbitrary channel that sockets can `join` and `leave`. It can be used to broadcast events to a subset of clients

### How do you join a room?
`join`
### how do you leave a room?
`leave`

## [Namespaces](https://socket.io/docs/v4/namespaces/)

### What is a Namespace and what does it allow you to do?
A Namespace is a communication channel that allows you to split the logic of your application over a single shared connection (also called "multiplexing").

### Each namespace potentially has its own what? (hint: 3 things)
- Event handlers
- Rooms
- middlewares

### Discuss a possible use case for separate namespaces

When building a communication application with multiple chat rooms.

