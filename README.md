# RealTimeChatApp

A simple real-time chat application written in Java. This project allows multiple clients to connect to a server and exchange messages in real time.

## Features

- **Multi-Client Support**: Multiple clients can connect to the server and send messages.
- **Broadcast Messaging**: Messages from one client are broadcasted to all other connected clients.
- **Real-Time Communication**: Uses Java sockets and multi-threading for seamless chat functionality.
## File Structure

-  **ChatServer.java:** Manages incoming connections and broadcasts messages to all clients.
- **ChatClient.java:** Connects to the server, sends, and receives messages.
- **ClientHandler.java:** Handles each client connection on the server.
## Usage

1. **Start the Server**:
   ```bash
   javac src/main/ChatServer.java && java -cp src/main ChatServer

2. Start the Client (open multiple terminals to test multi-client support):
    ```bash
    javac src/main/ChatClient.java && java -cp src/main ChatClient