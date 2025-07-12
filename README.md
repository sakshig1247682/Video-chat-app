# 🧑‍💻 Video Chat Application

A simple React-based **1-on-1 Video Calling App** built using [ZegoCloud UIKit](https://www.zegocloud.com/uikit) and React Router. This app allows users to enter their name and instantly join or create a private video chat room.

---

## 🚀 Features

- 🔒 Unique Room IDs for secure 1-on-1 meetings
- 🧑‍🤝‍🧑 Peer-to-peer video calling using ZegoUIKit
- 🔗 Shareable meeting links
- ⚡ Fast and lightweight frontend using React
- 🧭 React Router v6 for navigation

---

## 🛠️ Tech Stack

- **React.js**
- **React Router DOM**
- **ZegoCloud UIKit Prebuilt**
- **Vite** (for fast development)

---

## 📦 Installation

### 1. Clone the repository

```bash
git clone https://github.com/sakshig1247682/Video-chat-app.git
cd video-chat-app

### 2. Install dependencies
```bash
npm install

### 3. Setup environment variables
Create a .env file in the root directory:

VITE_APP_ID=your_zegocloud_app_id
VITE_SERVER_SECRET=your_zegocloud_server_secret
✅ You can get your App ID and Server Secret by signing up at ZegoCloud Console.

### 4. Run the app
npm run dev
The app will run locally at: http://localhost:5173

###  How It Works
User enters their name on the HomePage.

App navigates to a unique route /room/:id based on the entered name.

A room ID is either generated or fetched from the URL query.

ZegoCloud SDK initializes the video call using App ID and Server Secret.

User can share the link to invite someone to the same video room.

### Project Structure

├── Components/
│   ├── HomePage.jsx
│   └── VideoPage.jsx
├── App.jsx
├── main.jsx
├── .env
└── package.json

###📌 Important Notes
This is for testing/demo purposes using generateKitTokenForTest. For production, always use secure server-side token generation.

Ensure your App ID is a number in .env (not a string).

###📃 License
MIT License. Free to use and modify.

###🤝 Support
Feel free to contribute, open issues, or suggest features!
