# Java Socket Chat App

A simple multi-client chat application using Java Sockets. The server accepts connections and broadcasts messages to all connected clients. The client includes a small Swing GUI where users enter a display name, connect, and chat.

## How to Run

### Start the Server
javac Server.java
java Server

### Start the Client (GUI)
javac Client.java SimpleGUI.java
java SimpleGUI


### Description
- The server runs with no GUI and manages connected clients.
- The client GUI lets you:
  - Enter a name
  - Connect to the server
  - Send/receive messages in real time
- If the server disconnects, the client returns to the name screen and shows a notification.

## Files
- Server.java — handles client connections and message broadcasting
- Client.java — socket connection + send/receive logic
- SimpleGUI.java — Swing interface for chatting
```
