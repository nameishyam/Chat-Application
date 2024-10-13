# Chat Application

A real-time chat application built with Node.js, Express, and Socket.IO, allowing users to communicate with each other through a user-friendly interface. This application is designed to provide a smooth and engaging chatting experience with features like room-based chat, message notifications, and more.

## Features

- **Real-time Messaging**: Messages are delivered instantly using WebSockets for a seamless chat experience.
- **Room-based Chat**: Users can create or join specific chat rooms to communicate with others.
- **User Notifications**: Receive notifications when new users join the chat room or when a new message is received.
- **Responsive Design**: A user interface that adapts to different screen sizes, providing a good experience on both desktop and mobile devices.

## Technologies Used

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Node.js, Express
- **Real-time Communication**: Socket.IO

## Installation

Follow these steps to set up the Chat Application on your local machine:

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/nameishyam/Chat-Application.git
   cd Chat-Application
   ```

2. **Install Dependencies**:

   Ensure you have Node.js installed, then run:

   ```bash
   npm install
   ```

3. **Run the Application**:

   Start the server with:

   ```bash
   npm start
   ```

   The chat server will run on `http://localhost:3000`.

4. **Access the Application**:

   Open your browser and navigate to `http://localhost:3000` to start chatting!

## Usage

- Enter a username to join the chat.
- Select or create a chat room.
- Send messages to other users in the same room.
- Notifications will alert you when a user joins or leaves a room.

## Folder Structure

- **public/**: Contains frontend files (HTML, CSS, JavaScript).
- **src/**: Contains the backend server code.
- **views/**: Contains the views for the application.
- **server.js**: Entry point for the application.

## Contributing

Contributions are welcome! If you have ideas for improvements or new features, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Make your changes and commit them (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

## Acknowledgments

- [Node.js](https://nodejs.org/)
- [Express](https://expressjs.com/)
- [Socket.IO](https://socket.io/)
