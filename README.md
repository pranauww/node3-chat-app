# Chat Application

## Overview
This is a real-time chat application built using Node.js, Express, and Socket.io, allowing users to join chat rooms, send messages, and share their location. The app also provides a list of active users in each room.

## Features
- Join specific chat rooms with unique usernames.
- Send and receive messages in real-time.
- Share current location with other users in the room.
- Display the list of users in the room.
- Messages and locations are timestamped.
- Auto-scroll for messages.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/chat-app.git
   ```
2. Navigate to the project directory:
   ```bash
   cd chat-app
   ```

3. Install the dependencies:
   ```bash
   npm install
   ```

4. Start the server:
   ```bash
   npm run dev
   ```

5. Open your browser and navigate to:
   ```
   http://localhost:3000
   ```

### Main Files

- **index.js**: Initializes the Express server and Socket.io, handles connection events, manages chat rooms, and broadcasts messages.
- **messages.js**: Contains helper functions to generate message objects and location messages.
- **users.js**: Manages user data (add, remove, retrieve users) and handles rooms.
- **chat.js**: Front-end script that handles user input, form submission, and Socket.io communication.

## Usage

1. Open the application in the browser.
2. Join a room by entering your display name and the room name.
3. Start chatting with other users in the room!
4. Use the "Send location" button to share your current location with everyone in the room.

## Dependencies
- **express**: Web framework for Node.js.
- **socket.io**: Enables real-time, bi-directional communication between web clients and servers.
- **nodemon**: Utility to automatically restart the server on code changes (for development).

## Scripts

- **start**: Runs the application using Node.js.
- **dev**: Runs the application with `nodemon` for development, automatically restarting on changes.

## Contributions
Feel free to submit issues or pull requests for improvements or bug fixes!
