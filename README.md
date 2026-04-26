# 🔮 AstroConnect – Real-Time Astrology Consultation Platform

AstroConnect is a full-stack real-time platform that connects users with astrologers for live consultations, chat, and booking sessions.

---

## 🚀 Features

- 🔐 JWT Authentication & Role-Based Access (User / Astrologer / Admin)
- 💬 Real-time chat using WebSockets
- 📅 Appointment booking system
- 💰 Wallet-based billing system (planned / partial)
- 🧑‍💼 Admin dashboard for astrologer management
- ⚡ Scalable backend APIs for concurrent users

---

## 🏗️ Architecture

Client (React) → Backend API (Node.js/Express) → Database (PostgreSQL)  
                                 ↘ WebSocket Server (Real-time communication)

---

## 🧰 Tech Stack

**Frontend**
- React.js
- TypeScript
- Tailwind CSS

**Backend**
- Node.js
- Express.js
- Prisma ORM
- PostgreSQL

**Real-Time**
- WebSockets (ws)

**DevOps**
- AWS (EC2, S3)
- Docker
- CI/CD (GitHub Actions)

---

## 🔗 Repositories

- Frontend: https://github.com/Nitish490388/Astro-Connect-client
- Backend: https://github.com/Nitish490388/AstroConnect-server

---


```bash
# Clone frontend
git clone https://github.com/Nitish490388/Astro-Connect-client.git

# Clone backend
git clone https://github.com/Nitish490388/AstroConnect-server.git
