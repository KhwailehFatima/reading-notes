## OSI Model

### The OSI model consists of 7 layers of networking.

 In the OSI model, layers are organized from the most tangible and most physical, to less tangible and less physical but closer to the end user.
  
Layer 1:  Please | Physical Layer

Layer 2: Do | Data Link Layer

Layer 3: Not | Network Layer

Layer 4: Tell (the) | Transport 
Layer

Layer 5: Secret | Session Layer

Layer 6: Password (to) | Presentation Layer

Layer 7: Anyone | Application Layer

## Socket.io

Socket.IO is a library that enables low-latency, bidirectional and event-based communication between a client and a server.

It is built on top of the WebSocket protocol and provides additional guarantees like fallback to HTTP long-polling or automatic reconnection.

The following example attaches socket.io to a plain Node.JS HTTP server listening on port 3000.

const server = require('http').createServer();

const io = require('socket.io')(server);

io.on('connection', client => {

  client.on('event', data => { /* … */ });

  client.on('disconnect', () => { /* … */ });

});

server.listen(3000);

### Socket.IO is an event-driven library for real-time web applications. It enables real-time, bi-directional communication between web clients and servers. It consists of two parts: a client-side library that runs in the browser, and a server-side library for Node.js. Both components have a nearly identical API.