# 💬 Full Stack Realtime Chat Application

This is a full-featured real-time chat application developed using the MERN stack (MongoDB, Express.js, React.js, Node.js) along with Socket.io for bi-directional communication. The application is designed to support authenticated users, live chat features, and dynamic online user status with a clean, responsive interface.

---

## 📌 Project Overview

The primary goal of this application is to demonstrate the use of modern web technologies to build a scalable, responsive, and efficient real-time communication platform. It includes:
- Secure user registration and login
- Real-time messaging with instant delivery
- Display of online/offline users
- Global state management
- Optimized frontend with utility-first styling

---

## ✨ Core Features

- MERN stack architecture
- Real-time chat functionality using Socket.io
- JWT-based authentication and authorization
- Online/offline presence indicator
- Zustand for client-side state management
- TailwindCSS and Daisy UI for responsive and consistent design
- Cloudinary integration for media/file uploads
- Server-side and client-side error handling
- Deployed using free hosting solutions

---

## 🧰 Technologies Used

### Frontend:
- React.js
- Zustand (state management)
- TailwindCSS
- Daisy UI

### Backend:
- Node.js
- Express.js
- MongoDB (with Mongoose)
- Socket.io
- JSON Web Tokens (JWT)

### DevOps & Utilities:
- Cloudinary for file uploads

---

## ⚙ Environment Configuration

Set up a .env file in the root of the backend directory with the following variables:

```env
MONGODB_URI=your_mongodb_uri
PORT=5001
JWT_SECRET=your_jwt_secret

CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_key
CLOUDINARY_API_SECRET=your_cloudinary_secret

NODE_ENV=development
