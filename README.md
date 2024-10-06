# PyChat 🐍💬  
A simple, real-time chat application built using Flask and Socket.IO. PyChat gives users random usernames and avatars, creating a fun and engaging chat experience.

## Features ✨
- 🔄 Real-time messaging using Flask-SocketIO
- 🖼️ Random avatars and usernames for each user
- 🌐 Broadcast system for chat join/leave notifications
- 🖋️ Option to update your username on the go
- 🎨 Clean and responsive user interface

## Installation 🛠️
1. Clone the repo:
   ```bash
   git clone https://github.com/mhdZhHan/pychat-app.git
   ```
2. Navigate to the project directory:
   ```bash
   cd pychat-app
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the Flask app:
   ```bash
   flask run
   ```

## Usage 🚀

1. Open your browser and go to:
   ```arduino
   http://localhost:5000
   ```

Start chatting! 🎉

## WebSocket Events 🎧
- **connect:** Triggers when a user joins the chat. The user gets a random username and avatar.
- **send_message:** Broadcasts a new message to all users.
- **update_username:** Allows users to change their username.
- **disconnect:** Handles user leaving the chat.

## Contributing 🛠️

Feel free to submit issues or fork the repository and create pull requests.
