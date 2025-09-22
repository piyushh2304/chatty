

# 💬 Chatty

A **real-time chat application** built with the **MERN stack** (MongoDB, Express, React, Node.js) and **WebSockets (Socket.IO)** for seamless two-way communication.

🚀 Chatty lets users connect instantly, exchange messages in real-time, and experience a smooth chatting interface similar to modern messaging apps.

---


WEBSITE LINK : https://fullstack-chat-app-5f9u.onrender.com/


## ✨ Features

* 🔑 **Authentication** – Secure user signup & login with JWT
* 👥 **Real-time Messaging** – Powered by Socket.IO
* 📡 **Online/Offline Status** tracking
* 💬 **One-to-One & Group Chat** support
* 🔔 **Instant Notifications** for new messages
* 📱 **Responsive UI** – Works across desktop and mobile
* 🗂 **MongoDB Database** – Stores users, messages, and conversations

---

## 🛠 Tech Stack

**Frontend:** React, TailwindCSS / Material UI
**Backend:** Node.js, Express.js
**Database:** MongoDB (Mongoose ODM)
**Real-time Communication:** Socket.IO (WebSockets)
**Authentication:** JWT + bcrypt

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/chatty.git
cd chatty
```

### 2️⃣ Setup Backend

```bash
cd server
npm install
```

Create a `.env` file in `/server` with the following variables:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
```

Run the backend:

```bash
npm start
```

### 3️⃣ Setup Frontend

```bash
cd client
npm install
```

Create a `.env` file in `/client` with:

```env
REACT_APP_BACKEND_URL=http://localhost:5000
```

Run the frontend:

```bash
npm start
```

---

## 🚀 Usage

1. Open `http://localhost:3000` in your browser
2. Register/Login with an account
3. Start chatting in real-time! 🎉

---

## 📂 Project Structure

```
chatty/
│
├── frontend/       # React frontend
├── backend/       # Express backend
│   ├── models/   # MongoDB models
│   ├── routes/   # API routes
│   ├── socket/   # WebSocket (Socket.IO) events
│   └── ...
└── README.md
```

---

## 📌 Roadmap

* [ ] File sharing support (images, docs)
* [ ] Emoji picker
* [ ] Voice/Video calling
* [ ] Push notifications

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repo
2. Create a new branch (`feature/your-feature`)
3. Commit changes and push
4. Open a pull request

---

## 👨‍💻 Author

**Piyush Rajput**

---
