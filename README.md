# Realtime Code Editor

Live Preview: [Realtime Code Editor](#)

## Overview
Realtime Code Editor is a full-stack collaborative coding platform built with the MERN stack (React, Node.js, Express, MongoDB) and Socket.IO. It enables users to join or create rooms and edit code together in real time, making it ideal for pair programming, interviews, and collaborative learning.

## Features
- **Real-Time Collaboration:** Multiple users can edit code simultaneously in a shared room.
- **Room Management:** Create or join rooms using unique Room IDs.
- **Live User List:** See who is connected in your room.
- **Instant Code Sync:** All code changes are broadcast instantly to all participants.
- **Syntax Highlighting:** Powered by CodeMirror for a smooth editing experience.
- **Notifications:** Toast messages for user actions and errors.

## Tech Stack
### Frontend
- React
- CodeMirror
- React Router
- React Hot Toast
- CSS

### Backend
- Node.js
- Express.js
- Socket.IO

## Installation

### Prerequisites
- Node.js (v14 or higher)
- npm

### Setup
1. **Clone the repository:**
   ```sh
   git clone https://github.com/your-username/realtime-code-editor.git
   cd realtime-code-editor
   ```
2. **Install dependencies:**
   ```sh
   npm install
   ```

### Running the App
- **Development:**
  ```sh
  npm run start:front   # Start React frontend
  npm run server:dev    # Start backend server with nodemon
  ```
- **Production:**
  ```sh
  npm run build
  npm start
  ```

The app will be available at `http://localhost:3000`.

## Usage
- Open the app in your browser.
- Create a new room or join an existing one using a Room ID.
- Share the Room ID with others to collaborate in real time.

## Folder Structure
```
realtime-code-editor/
├── build/           # Production build files
├── public/          # Static files
├── src/             # React source files
│   ├── components/  # UI components (Editor, Client)
│   ├── pages/       # Main pages (Home, EditorPage)
│   └── ...          # Other source files
├── server.js        # Express and Socket.IO server
├── package.json     # Project dependencies and scripts
└── README.md        # Project documentation
```

## Contributing
Contributions are welcome! Please follow these steps:
1. Fork the repository
2. Create a new branch (`git checkout -b feature/improvement`)
3. Make your changes
4. Commit your changes (`git commit -am 'Add new feature'`)
5. Push to the branch (`git push origin feature/improvement`)
6. Submit a Pull Request

## Contact
If you have any questions or suggestions, please feel free to reach out:
- GitHub Issues:ShubhamBhowmik11
- Email: your-shubhambhowmik106325@gmail.com

---
MIT License
