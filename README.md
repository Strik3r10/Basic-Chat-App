# 🗨️ Basic Chat App

A simple and clean real-time chat application built with:

-   **Node.js + Express** (Backend)
-   **MongoDB + Mongoose** (Database)
-   **Socket.io** (Real-time messaging)
-   **React + Vite** (Frontend)
-   **Zustand & Context API** (State Management)

The app supports authentication, live chat, and persistent message
storage.

## 🚀 Features

-   🔐 **User Authentication** (Register & Login)
-   🧑‍🤝‍🧑 **Start conversations** with any user
-   ⚡ **Real-time messaging** using Socket.io
-   💬 **Persistent conversations** stored in MongoDB
-   📱 **Clean and responsive UI**
-   🌐 **Get all users & messages via API**
-   🔒 **Protected routes** using JWT middleware

## 🛠️ Tech Stack

**Frontend:** React, Vite, Zustand, Context API\
**Backend:** Node.js, Express\
**Database:** MongoDB & Mongoose\
**Real-time:** Socket.io

## 📁 Project Structure

    Basic-Chat-App/
    │
    ├── Backend/
    │   ├── Models/
    │   ├── Route/
    │   ├── Socket/
    │   ├── middleware/
    │   └── index.js
    │
    └── Frontend/
        ├── src/
        ├── public/
        └── main Vite setup

## 🔌 Backend Overview

The backend handles:

-   User registration & login
-   JWT-based authentication
-   Starting conversations
-   Sending & receiving messages
-   Establishing real-time events

### Main Routes

  Route            Purpose
  ---------------- ---------------------
  `/api/auth`      Register, Login
  `/api/user`      Get users
  `/api/message`   Send & get messages

## ⚡ Real-Time Messaging

The project uses **Socket.io** for instant communication:

-   Each user joins their **own private room**
-   Messages are emitted directly to receiver rooms
-   Updates appear instantly on the frontend

## 🎨 Frontend Overview

The React frontend includes:

-   Login & Register pages
-   Home screen with Sidebar + Chat Window
-   Zustand store for conversation & messages
-   Context API for authentication
-   Auto-verifying JWT on protected pages

## 🏁 Getting Started

### 1️⃣ Backend Setup

    cd Backend
    npm install

Create a `.env` file:

    PORT=5000
    MONGO_URI=your-mongodb-uri
    JWT_SECRET=your-secret

Start backend:

    npm run dev

### 2️⃣ Frontend Setup

    cd Frontend
    npm install
    npm run dev

Frontend runs on:\
**http://localhost:5173**

## 🚧 Future Improvements

-   Group chats
-   File/image sharing
-   Typing indicators
-   Online/offline status
-   Better UI components

## 👤 Author

**Name:** Owais Farooqui\
**LinkedIn:** https://in.linkedin.com/in/owais-farooqui-942281256
