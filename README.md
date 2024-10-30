# Chat Web App

Chat Web App is a real-time messaging application built with a multi-directory architecture, enabling scalable and efficient communication. The application is split into three main directories: `api` (for backend REST API), `socket` (for real-time WebSocket server), and `client` (for frontend client).

## Features

- **Real-Time Messaging**: Instantly send and receive messages using WebSockets.
- **User Authentication**: Secure login and registration with JWT-based authentication.
- **Group & Private Chats**: Supports both private one-on-one chats and group conversations.
- **Notifications**: Real-time notifications for incoming messages and online/offline statuses.
- **Responsive Design**: Optimized for desktop and mobile devices.

## Directory Structure

- **api**: Handles authentication, user management, and database interactions.
- **socket**: Manages WebSocket connections for real-time messaging.
- **client**: The frontend client built with React, providing an intuitive chat interface.

## Getting Started

### Prerequisites

Ensure you have the following installed on your machine:
- Node.js
- MongoDB (or a MongoDB URI if using a cloud database)

### Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/Moksh91119/chat-web-app.git
    ```

2. **Install dependencies** for each directory:

    Navigate to the `api` directory and install backend dependencies:
    ```bash
    cd api
    npm install
    ```

    Navigate to the `socket` directory and install dependencies:
    ```bash
    cd ../socket
    npm install
    ```

    Finally, navigate to the `client` directory and install frontend dependencies:
    ```bash
    cd ../client
    npm install
    ```

3. **Set up environment variables**:

    Create a `.env` file in the `api` and `socket` directories with the following variables:

    For `api`:
    ```plaintext
    MONGO_URL=your_mongodb_url
    ```

4. **Run the application**:

    Start the backend API server:
    ```bash
    cd api
    npm start
    ```

    Start the WebSocket server:
    ```bash
    cd ../socket
    npm start
    ```

    Start the frontend client:
    ```bash
    cd ../client
    npm start
    ```

5. **Access the application**:

    Open your browser and go to `http://localhost:3000` to start using the Chat Web App.

## Contact

If you have any questions or need further assistance, feel free to contact me:

- **Email**: [jainmoksh03@gmail.com](mailto:jainmoksh03@gmail.com)
- **Portfolio**: [itsmemoksh.in](https://itsmemoksh.in/) - Learn more about me and explore my other projects.

---

Feel free to open issues or contribute to the project. Your feedback and contributions are always welcome!
