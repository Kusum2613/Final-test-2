# 🎫 Ticketing System

A full-stack ticketing system platform built with **React.js**, **Node.js**, **Express**, and **MongoDB**. This project allows users to sign up, raise tickets, manage teams, track analytics, and interact through a chatbot.

---

## 🔗 Live Demo

- **Frontend**: [https://ticketing-system-mgb4.vercel.app/](https://ticketing-system-mgb4.vercel.app/)
- **Backend**: [https://ticketing-system-usx8.onrender.com](https://ticketing-system-usx8.onrender.com)

---

## 🚀 Tech Stack

### Frontend:
- React.js
- CSS 
- Recharts (for analytics)
  
### Backend:
- Node.js
- Express.js
- MongoDB
- JWT for authentication
- Bcrypt for password hashing

---

## 🔧 Setup Instructions

### 🔹 Frontend

```bash
git clone <frontend-repo-url>
cd <project-folder>
npm install
npm install recharts
npm run dev
```

### 🔹 Backend

```bash
git clone <backend-repo-url>
cd <project-folder>
npm install
# Create a `.env` file in the root with the following:
# MONGO_URI=<your-mongodb-uri>
# JWT_SECRET=<your-secret-key>
# PORT=5000 (or any preferred port)
npm run dev
```

---

## ✅ Features Implemented

### 🔐 Authentication
- Sign-up and login system using email and password
- JWT-based session management
- Passwords are securely hashed using `bcrypt`

### 🧑‍💼 User Roles
- Supports multiple admins, each with their own team members
- Team members must register using emails given by admin and the password too.

### 🏠 Landing Page
- Simple public-facing landing page (desktop view)

### 📊 Dashboard
- All Tickets
- Resolved Tickets
- Unresolved Tickets

### 🎫 Ticket Management
- Users can raise tickets
- Admins can mark tickets as Resolved or Unresolved
- Default ticket assignment to Admin

### 👥 Team Management
- Add, remove, and manage team members via a dedicated Team page

### 📈 Analytics Page
- View performance charts and ticket resolution insights using Recharts

### 💬 Chat System
- Customer support chat interface
- Missed chat timer marks unattended chats

### 🤖 Chatbot Customization
- Admins can customize chatbot widget appearance and behavior

### 🌐 Dummy Website with Embedded Chatbot
- A separate page to preview the chatbot in a real environment

### ✏️ Edit Profile
- Users can edit their name, email, and other profile details

---

## 🛡️ Best Practices Followed

- Passwords are stored in encrypted format
- Form inputs validated on both frontend and backend
- Proper error handling throughout the application
- Project follows modular structure and naming conventions
- No CSS frameworks or libraries used

---

## 📂 Folder Structure Highlights

```
├── frontend/          # Frontend code (React)
├── backend/          # Backend code (Node.js + Express)
├── .env             # Environment variables (not pushed to GitHub)
├── README.md
```

---

## 🧪 Demo Credentials

> You can register with your own email for testing.

---

## 📝 Notes

- Ensure `.env` is **never pushed to GitHub**. Add `.env` in `.gitignore`.
- The project is deployed using **Vercel (Frontend)** and **Render (Backend)**.
