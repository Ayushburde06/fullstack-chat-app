
# 💬 Fullstack Chat App

A real-time, modern **Fullstack Chat Application** built with **MERN Stack (MongoDB, Express.js, React.js, Node.js)**. This application allows users to register, login, chat in real-time, and manage conversations efficiently.

![Chat App Banner](https://img.freepik.com/free-vector/chatting-concept-illustration_114360-1402.jpg) <!-- You can replace this with your own hosted image -->

---

## 🚀 Features

- 🧑‍🤝‍🧑 User Authentication (JWT-based)
- 💬 Real-Time Messaging with Socket.io
- 🔒 Secure Login and Registration
- 📁 Chat List and Message Threads
- ✅ REST API for all backend operations
- 📱 Responsive Frontend using React

---

## 🛠️ Tech Stack

**Frontend:**
- React.js
- Axios
- Context API / Redux (optional)
- CSS / Tailwind / Bootstrap

**Backend:**
- Node.js
- Express.js
- MongoDB + Mongoose
- JWT Authentication
- Socket.IO for real-time features

---

## 📁 Folder Structure

fullstack-chat-app/
├── backend/ # Express + MongoDB server
│ ├── config/ # DB configs, JWT, etc.
│ ├── controllers/ # Route logic
│ ├── models/ # Mongoose models
│ ├── routes/ # API endpoints
│ └── server.js # Main server entry
│
├── frontend/ # React client
│ ├── public/
│ ├── src/
│ │ ├── components/
│ │ ├── pages/
│ │ ├── context/
│ │ └── App.js
│ └── package.json
│
├── README.md
└── LICENSE


---

## 🧪 Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/Ayushburde06/fullstack-chat-app.git
cd fullstack-chat-app
2. Backend Setup
bash
Copy
Edit
cd backend
npm install
npm start
Create .env file inside backend/ with:

env
Copy
Edit
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
3. Frontend Setup
bash
Copy
Edit
cd frontend
npm install
npm start
App will run on: http://localhost:3000ss
