# ChatLooper

ChatLooper is a brand new (closed-source) alternative to… well, nothing really. Created just for fun as my first React + Vite project.

## Features

* **Persistent chat history**: messages remain visible to all users who join.
* **Customizable user nicknames**: each participant can choose their own display name.
* **Image sharing**: send photos directly within the chat.
* **System messages**: notifications for important events, such as users joining.
* **Custom user profiles**: set your display name, status, bio, and profile picture.
* **Typing indicator**: see when someone is typing a message.
* **Reply to messages**: directly reply to specific messages.

## Demo

Access the app online with no registration required:
[ChatLooper 1.3](https://chatlooper.up.railway.app)

## Technologies Used

* React (with Hooks)
* Vite
* Socket.IO (WebSocket real-time communication)
* Node.js (Backend server)
* Modern CSS with glassmorphism effects inspired by iOS 16/17

## Project Structure

* **Frontend**: React-based user interface featuring full chat functionality, profile management, and image upload support.
* **Backend**: Node.js server handling authentication, persistent message storage, and real-time communication via Socket.IO.

## Getting Started

To run ChatLooper locally, clone this repository and follow these steps:

```bash
# Install dependencies for frontend and backend
npm install

# Start the backend server
node index.js

# Start the frontend development server
npm run dev
```

## License

This project is closed-source and for personal/fun use only.

---

Feel free to try it out and join the conversation! :3
