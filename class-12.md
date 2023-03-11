# Class 12 Reading Notes

## Web Sockets

1. What is a Web Socket?
  It is a computer communications protocol. It allows communication between channels.

2. Describe the Web Socket request/response handshake and what happens once the connection is established.
  The websocket handshake would use the HTTP Upgrade Header to change the protocol to WebSocket. This would then allow communication between a browser and a server.

3. Web Sockets provide a standardized way for the server to send content to a client without first receiving a __request__ from that client.

## Socket.io Tutorial

1. What does the event handler io.on() do?
  The .on() listens

2. Describe some possible proof of life or proof that the code works as expected
  There would be a communication between the events.

3. What does socket.emit() do?
  socket.emit() sends out the event so that it could be listened to by any .on().

## Socket.io vs Web Sockets

1. What is the difference between WebSocket and Socket.IO? (think Git and GitHub, or OAuth and Auth0).
  socket.io is the library that enables communication, while webSocket is tje protocol.

2. When would you use Socket.IO?
  if you would like a communication between client and server in real time.

3. When would you use WebSockets?
  if you would like a communication between client and server in real time. sorry these are the same I just feel it is the same response.

## OSI model explained

 The OSI model has seven different layers, application, presentation, session, transport, network, data link and physical.
 