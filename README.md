# CHAT-APPLICATION
*COMPANY*: CODTECH IT SOLUTIONS
*NAME*: SAINATH DIGAMBAR WAKHURE
*INTERN ID*: CT12WSAF
*DOMAIN*: FULL STACK WEB DEVELOPMENT
*DURATION*: 12 WEEKS 
*MENTOR*: NEELA SANTOSH KUMAR

This project is a Real-Time Chat Application built with Node.js and Socket.IO.
It is designed to allow multiple users to join a chatroom and send messages to each other instantly without needing to refresh the page. The messages appear to everyone in real-time, just like WhatsApp group chats or Messenger rooms.

- How It Works
The project mainly has two parts:

Backend Server (written in Node.js with Socket.IO)

Frontend Client (usually a simple HTML page that connects to the server)

The server is responsible for:

Setting up a WebSocket connection (a fast way for websites to send and receive messages instantly).

Handling events like when a user joins, sends a message, or leaves the chat.

Broadcasting the messages sent by one user to all other connected users.

The client is responsible for:

Sending a message typed by the user to the server.

Listening for messages from the server and displaying them on the chat screen.

Showing notifications when someone joins or leaves the chat.

The core technology behind this chat app is Socket.IO. Socket.IO is a JavaScript library that enables real-time, bi-directional communication between web clients and servers. It uses WebSocket internally but falls back to other methods if WebSocket is not available.

- In this project:

The server listens on a specific port (for example, 3000).

When a user connects to the app, the server establishes a socket connection.

Every time a user sends a message, it triggers a socket event.

The server catches this event and broadcasts the message to all connected users.

What's Inside the Project
Node.js Server: This is where the real magic happens. The server script (likely index.js or similar) sets up the server, manages users, and handles communication using the Socket.IO library.

Node Modules: These are libraries installed with npm (Node Package Manager). They help the server with various tasks like managing WebSocket connections, improving performance, etc.

Socket.IO: This special library enables real-time communication. It handles the complicated part of making web browsers talk to servers instantly.

You’ll find files like:

package.json: A file that keeps track of all installed libraries and project metadata.

index.js (or a similar server script): This is the main file that runs the server.

HTML/CSS/JS files (client side): These are used for the user interface (chat input, message display).

What Happens When You Run It
The Node.js server is started by running node index.js (or using a tool like nodemon).

The server listens for new client connections.

Users can open the web page, enter their name, and start chatting.

When a user sends a message, it's sent instantly to all connected users.

If a user leaves the chat, a notification is broadcast to everyone.

Key Features
Real-Time Messaging: Messages appear immediately without refreshing the page.

Multiple Users: Many users can chat at the same time.

User Notifications: You can see when someone joins or leaves.

Simple Setup: You only need Node.js installed to run this.

Summary
This chat application teaches important concepts like:

Using Socket.IO for WebSocket communication.

Handling real-time data flows.

Working with events (connect, message, disconnect).

Setting up a basic Node.js server.

Broadcasting messages to multiple clients.

It’s a perfect beginner-level project for learning about real-time web applications, server-client communication, and backend development with Node.js.

#Output :
![Image](https://github.com/user-attachments/assets/c0130e7e-c02c-4c9f-89ca-f80355b3a51a)


