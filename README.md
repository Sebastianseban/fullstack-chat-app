# Real-Time Chat App

## 🚀 Overview
A real-time chat application built with **MERN (MongoDB, Express, React, Node.js)**, integrated with **Socket.io** for instant messaging and **Zustand** for state management. 

### 🌟 Features:
- 🎃 **Authentication & Authorization** with JWT
- 👾 **Real-time messaging** using Socket.io
- 🚀 **Online user status tracking**
- 👌 **Global state management** with Zustand
- 🐞 **Robust error handling** (server & client-side)
- ⭐ **Deployment-ready** setup

## 🛠️ Tech Stack
- **Frontend:** React, TailwindCSS, Daisy UI
- **Backend:** Node.js, Express, MongoDB
- **Real-time Communication:** Socket.io
- **Authentication:** JWT (JSON Web Token)
- **Global State Management:** Zustand
- **Image Uploads:** Cloudinary

---

## 🔧 Setup & Installation

### 1️⃣ Clone the repository
```sh
git clone https://github.com/your-username/your-repository.git
cd your-repository
```

### 2️⃣ Setup the `.env` file (in the root directory)
Create a `.env` file and add the following:
```env
MONGODB_URI=your_mongodb_connection_string
PORT=5001
JWT_SECRET=your_jwt_secret

CLOUDINARY_CLOUD_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret

NODE_ENV=development
```

### 3️⃣ Install dependencies
#### 📌 Backend
```sh
cd backend
npm install
```

#### 📌 Frontend
```sh
cd ../frontend
npm install
```

### 4️⃣ Build & Start the App
#### 🚀 Backend
```sh
npm start
```

#### 🚀 Frontend
```sh
npm run dev
```




