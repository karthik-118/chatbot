# MERN Chat Application

A full-stack MERN (MongoDB, Express.js, React.js, Node.js) chat application with JWT (JSON Web Token) Authorization, password encryption, and real-time messaging using Socket.io.

## Features

- **Authentication:** JWT-based authentication system ensures secure access to the application.
- **Password Encryption:** User passwords are encrypted for enhanced security.
- **Real-time Messaging:** Chat with other users in real-time using Socket.io.
- **User Profile:** View profile picture, email, and username of the logged-in user.
- **User Search:** Search registered users from the database to initiate chats.
- **Group Creation:** Create groups and add/remove members to chat together in real-time.
- **Notifications:** Receive notifications for new unread messages.
- **Log-out:** Safely log out with a single button click.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/AnshNagpal0/ChitChat.git
   
   
2. Navigate to the project directory:
   
      ```bash
      cd mern-chat-app


3. Install dependencies for both server and client:
   
      ```bash
      npm install
      cd client
      npm install



4. Create a .env file in the root directory and set environment variables (e.g., MongoDB connection string, JWT secret).


5. Start the server:
   
      ```bash
      npm start


6. Start the client:

    ```bash
      cd client
      npm start


7. Visit http://localhost:3000 in your browser to use the application.
