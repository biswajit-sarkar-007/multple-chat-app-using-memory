# Socket.io Chat App with SQLite & Clustering

A real-time chat application using **Socket.io** for WebSocket connections, **SQLite** for memory management, and **Node.js clustering** for handling multiple users in the same room efficiently.

## Features
- **Real-time messaging** using WebSockets.
- **Multiple rooms support** to chat in different spaces.
- **SQLite for memory management**, ensuring lightweight and efficient data storage.
- **Node.js clustering** for handling multiple users in the same room.
- **Scalability** to manage concurrent connections seamlessly.

## Tech Stack
- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Node.js, Express.js, Socket.io
- **Database:** SQLite
- **Clustering:** Node.js `cluster` module

## Installation

1. **Clone the repository:**
   ```bash
   git clone  https://github.com/biswajit-sarkar-007/multple-chat-app-using-memory
   cd  multple-chat-app-using-memory
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Run the server:**
   ```bash
   node index.js
   ```

4. **Access the chat app:**
   Open your browser and navigate to `http://localhost:3000`

## Project Structure
```
├── node_modules/        # Node.js dependencies
├── .env                 # Environment variables
├── .gitignore           # Git ignore file
├── chat.db              # SQLite database file
├── index.html           # Frontend UI
├── index.js             # Main backend server with clustering
├── package-lock.json    # Lock file for dependencies
├── package.json         # Dependencies and scripts
└── README.md            # Documentation
```

## Usage
- Open the app and **enter a username**.
- Join or create a chat room.
- Send real-time messages with other users in the room.

## How It Works
- When a user connects, **Socket.io** establishes a WebSocket connection.
- The user can join an existing chat room or create a new one.
- Messages are broadcasted to all users in the room.
- **SQLite** handles temporary message storage.
- **Node.js Clustering** ensures optimal load distribution across multiple users.

## Contributing
1. Fork the repository.
2. Create a new branch (`feature-name`).
3. Commit your changes.
4. Push to your branch and open a Pull Request.

 

---
Made with ❤️ using Socket.io, SQLite, and Node.js!

