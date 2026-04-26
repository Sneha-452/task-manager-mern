# 📋 Task Manager (MERN Stack)

A full-stack Task Management Application built with the MERN stack (MongoDB, Express.js, React.js, Node.js). It allows users to register, log in, and manage tasks with a clean, modern UI and secure backend.

---
  Uplaod Link - https://taskmaster-lovat.vercel.app/
## 🚀 Features

- 🔐 User Authentication – Register & Login with JWT-based authentication
- 📝 Task CRUD Operations – Create, Read, Update, and Delete tasks
- 🎯 Task Status Management – Mark tasks as completed or pending
- 🔍 Filtering & Search – Quickly find tasks
- 📱 Responsive UI – Works on all devices
- 💾 MongoDB Database – Store tasks and user data securely
- ⚡ Fast API – Built with Express & Node.js
- 🎨 Modern Styling – Tailwind CSS + custom components
- 🌐 Deployed – Easy to run locally or on a server

---

## 🛠 Tech Stack

**Frontend**
- React.js
- Tailwind CSS
- Axios (API calls)
- React Router DOM

**Backend**
- Node.js
- Express.js
- MongoDB + Mongoose
- JSON Web Token (JWT) for authentication
- bcrypt.js for password hashing
- dotenv for environment variables

---

## 📂 Folder Structure

```
Task-Manager-MERN/
├── client/                   # Frontend (React)
│   ├── public/               # Public assets
│   └── src/
│       ├── components/       # UI components
│       ├── pages/            # App pages (Login, Dashboard, etc.)
│       ├── utils/            # Helper functions
│       ├── App.js
│       └── index.js
├── server/                   # Backend (Node + Express)
│   ├── config/               # DB connection
│   ├── controllers/          # Route controllers
│   ├── middleware/           # Authentication middleware
│   ├── models/               # Mongoose schemas
│   ├── routes/               # API routes
│   ├── .env.example          # Example env file
│   └── server.js
├── package.json              # Root package (may use concurrently)
└── README.md
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository
```bash
git clone https://github.com/sahilzalte/Task-Manager-MERN.git
cd Task-Manager-MERN
```

### 2️⃣ Install dependencies
```bash
cd server
npm install
cd ../client
npm install
```

### 3️⃣ Environment variables
Create a server/.env file:
```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
```

### 4️⃣ Start the app
From the project root:
```bash
npm run dev
```
