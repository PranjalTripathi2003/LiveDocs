# Live Docs

## Overview

Live Docs is a Google Docs clone developed using React, Socket.io, and MongoDB. This project allows multiple users to collaboratively edit documents in real-time, leveraging modern web technologies to provide a seamless user experience.

## Project Structure

```plaintext
Live_Docs/
│
├── client/
│   ├── node_modules/
│   ├── public/
│   ├── src/
│   ├── package-lock.json
│   ├── package.json
│   └── README.md
│
├── server/
│   ├── node_modules/
│   ├── Document.js
│   ├── package-lock.json
│   ├── package.json
│   ├── server.js
│   └── README.md
│
└── README.md
```

## Key Features

1. **Real-time Collaborative Editing**: Multiple users can edit the same document simultaneously, with changes reflected in real-time.
2. **Text Formatting**: Users can format text using various styles provided by the Quill text editor.
3. **Document Storage**: Documents are stored in MongoDB, allowing for persistent data storage and retrieval.
4. **Document Management**: Users can create new documents, share them with others, and undo/redo changes.

## Installation and Setup

### Prerequisites

- Node.js
- MongoDB
- npm (Node Package Manager)

### Client Setup

1. Navigate to the `client` directory:
   ```bash
   cd client
   ```

2. Install the required dependencies:
   ```bash
   npm install
   ```

3. Start the client:
   ```bash
   npm start
   ```

### Server Setup

1. Navigate to the `server` directory:
   ```bash
   cd server
   ```

2. Install the required dependencies:
   ```bash
   npm install
   ```

3. Start the server:
   ```bash
   node server.js
   ```

### MongoDB Setup

Ensure MongoDB is installed and running on your machine. You can download and install MongoDB from the [official website](https://www.mongodb.com/try/download/community).

## Usage

1. Open your browser and navigate to the client application (typically at `http://localhost:3000` if using the default React setup).
2. Create or open a document.
3. Share the document URL with collaborators.
4. Start editing and see changes in real-time!

## Development Process

1. **Project Setup**: Created a new React project and installed necessary dependencies, including Quill, Socket.io, and MongoDB.
2. **Text Editor Component**: Developed a text editor component using the Quill library to allow text editing and formatting.
3. **Server Setup**: Set up a Node.js server with Express.js to handle WebSocket connections using Socket.io and database interactions with MongoDB.
4. **Real-time Communication**: Implemented real-time communication between clients using Socket.io, enabling multiple users to edit the same document simultaneously.
5. **Data Storage**: Utilized MongoDB for document data storage, allowing for saving and retrieving documents.
6. **Document Synchronization**: Implemented synchronization mechanisms to ensure all users see the same content.
7. **Additional Features**: Added features such as document creation, sharing, and undo/redo functionality.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the LICENSE file for details.
