# Chat Application - A simple online chat app.

## Description
This is a simple online chat application developed in Java. \
The application allows multiple users to connect to a central server, send messages, and receive messages from other users in real-time.

## Requirements

### Server Implementation
- **ChatServer.java Class:**
    - Use socket programming to manage connections from multiple clients.
    - Handle incoming connections, assign a unique user ID to each connected client, and maintain a list of connected users.

### Client Implementation
- **ChatClient.java Class:**
    - Connect to the server using sockets.
    - Send messages to the server, which will broadcast the messages to all connected clients.
    - Receive messages from other users.

### User Interface
- A simple text-based interface for the client to facilitate message input and display.

### Installation
- Step 1: Clone the repository (Run the following commands in a Terminal application): \
 \```sh \
 git clone https://github.com/yourusername/online-chat-application.git \
 cd online-chat-application 
- Step 2: Compile the source code using the following command: javac -d bin src/com/chatapp/server/ChatServer.java src/com/chatapp/client/ChatClient.java
- Step 3: Run the server: java -cp bin com.chatapp.server.ChatServer
- Step 4: Run the client: java -cp bin com.chatapp.client.ChatClient
