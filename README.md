# 💬 Real-Time Chat Application

![React](https://img.shields.io/badge/Frontend-React-blue)
![Node.js](https://img.shields.io/badge/Backend-Node.js-green)
![MongoDB](https://img.shields.io/badge/Database-MongoDB-brightgreen)
![Socket.io](https://img.shields.io/badge/Realtime-Socket.io-black)
![TailwindCSS](https://img.shields.io/badge/UI-TailwindCSS-38B2AC)
![License](https://img.shields.io/badge/License-MIT-yellow)

A **full-stack real-time 1:1 chat application** built with the **MERN stack** and **Socket.io** that allows users to communicate instantly with secure authentication and real-time updates.

---

# 🚀 Live Links

🌐 **Live Application:** https://real-time-chat-app-1-ef4c.onrender.com
💻 **GitHub Repository:** https://github.com/shankarpattanaik/real-time-chat-app

---

# 📌 Features

## 🔐 Authentication & Security

- Secure **JWT-based authentication**
- Protected routes for authorized users
- Password encryption using **bcrypt**

## 💬 Real-Time Messaging

- Instant 1:1 messaging using **Socket.io**
- Real-time message delivery
- Persistent message storage

## ⌨️ User Interaction

- Typing indicators
- Online / offline user status
- Real-time chat updates

## 📱 Responsive UI

- Mobile-first design
- Built with **Tailwind CSS**
- Clean and modern chat interface

## ⚡ State Management

- Global state handled using **Redux Toolkit**

---

# 🛠 Tech Stack

## Frontend

- React.js
- Redux Toolkit
- Tailwind CSS
- Axios
- Socket.io Client

## Backend

- Node.js
- Express.js
- Socket.io

## Database

- MongoDB
- Mongoose

## Authentication

- JWT (JSON Web Tokens)
- bcrypt

---

# 📂 Project Structure

```
real-time-chat-app
│
├── frontend/                # React Frontend
│   ├── src/
│   │   ├── components/
│   │   ├── customHooks/
│   │   ├── pages/
│   │   ├── redux/
│   │   └── assets/
│
├── backend/                # Node.js Backend
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middlewares/
│   ├── config/
│   └── socket/
│
└── README.md
```

---

# ⚙️ Installation

## 1️⃣ Clone the repository

```bash
git clone https://github.com/shankarpattanaik/real-time-chat-app.git
cd real-time-chat-app
```

---

## 2️⃣ Install Dependencies

### Backend

```bash
cd server
npm install
```

### Frontend

```bash
cd client
npm install
```

---

# 🔑 Environment Variables

Create a `.env` file inside the **server** directory.

```
PORT=8000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
CLOUD_NAME="cloud_name"
API_KEY="cloud_key"
API_SECRET="API_secret"
CLIENT_URL=http://localhost:3000

```

---

# ▶️ Running the Application

### Start Backend

```bash
cd server
npm run dev
```

### Start Frontend

```bash
cd client
npm start
```

Application will run at:

```
http://localhost:3000
```

---

# 📡 API Overview

## Auth Routes

| Method | Endpoint           | Description       |
| ------ | ------------------ | ----------------- |
| POST   | /api/auth/register | Register new user |
| POST   | /api/auth/login    | Login user        |

---

## Chat Routes

| Method | Endpoint   | Description     |
| ------ | ---------- | --------------- |
| GET    | /api/chats | Get user chats  |
| POST   | /api/chats | Create new chat |

---

## Message Routes

| Method | Endpoint              | Description       |
| ------ | --------------------- | ----------------- |
| GET    | /api/messages/:chatId | Get chat messages |
| POST   | /api/messages         | Send message      |

---

# 📸 Screenshots

Add screenshots of your application here.

Example:

```
/screenshots/login.png
/screenshots/chat.png
```

---

# 🚀 Deployment

You can deploy this application using:

- **Frontend:** Vercel / Netlify
- **Backend:** Render / Railway
- **Database:** MongoDB Atlas

---

# 🔮 Future Improvements

- 👥 Group Chat
- 📎 File & Image Sharing
- ✔ Message Read Receipts
- 🔔 Push Notifications
- 🌙 Dark Mode

---

# 🤝 Contributing

Contributions are welcome.

1. Fork the repository
2. Create your feature branch
3. Commit changes
4. Open a Pull Request

---

# 👨‍💻 Author

**Shankar Pattanaik**

GitHub:   https://github.com/shankarpattanaik
LinkedIn: https://www.linkedin.com/in/shankarpattanaik

---

⭐ If you like this project, please consider giving it a **star** on GitHub!
