# 🌐 Streamify – Real-Time Chat & Video Application

## 📘 Overview
**Streamify** is a full-stack web application that enables users to engage in secure, real-time chat and video calls.  
It integrates WebRTC for peer-to-peer communication and Socket.io for instant message updates.  
The app ensures low-latency connections and user authentication through JWT.

---

## 🎯 Objectives
- Build a modern **real-time communication** platform.
- Provide **instant chat**, **video calling**, and **file sharing** features.
- Maintain strong **security and privacy** using encryption and role-based access.

---

## 🧩 Tech Stack
| Layer | Technology |
|:------|:------------|
| Frontend | React (Vite), TailwindCSS |
| Backend | Node.js, Express.js |
| Database | MongoDB + Mongoose |
| Communication | Socket.io, WebRTC |
| Authentication | JWT, bcrypt |
| Deployment | Render / Vercel |

---

## 🚀 Installation & Setup

### Prerequisites
Ensure the following are installed:
- Node.js (>= 18)
- MongoDB (local or Atlas)
- npm or yarn

### Steps
```bash
# 1️⃣ Clone the repository
git clone https://github.com/<your-username>/streamify.git
cd streamify

# 2️⃣ Install dependencies
npm install

# 3️⃣ Configure environment variables
cp .env.example .env
# Add values for MONGO_URI, JWT_SECRET, and PORT

# 4️⃣ Start the development server
npm run dev
