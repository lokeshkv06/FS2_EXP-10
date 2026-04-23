# ⚡ EXP 10: WebSocket Real-Time Chat Application

A full-stack **real-time chat application** built using:

- 🌐 Frontend: React (Vite)
- 🔧 Backend: Spring Boot
- 🔌 Communication: WebSocket (STOMP + SockJS)

This project demonstrates **real-time bidirectional communication** between client and server.

---
<img width="1907" height="1025" alt="Screenshot 2026-04-23 143459" src="https://github.com/user-attachments/assets/65f94939-d6cf-4391-a515-8208a549dcaf" />
<img width="1919" height="1029" alt="Screenshot 2026-04-23 143512" src="https://github.com/user-attachments/assets/eab56d97-ce4e-409b-91e2-4acce620a6f2" />
<img width="1919" height="1027" alt="Screenshot 2026-04-23 143504" src="https://github.com/user-attachments/assets/a8388855-b491-46be-828e-fe62e6a48474" />

# 🚀 Features

- 💬 Real-time messaging (no refresh required)
- 👤 Username-based chat
- 🔁 Instant message broadcasting
- ⚡ WebSocket persistent connection
- 🌙 Modern dark UI
- 📡 Multi-user communication support

---

# 🏗️ Project Structure
EXP_10/
│
├── backend/ → Spring Boot WebSocket Server
│ ├── controller/
│ ├── config/
│ └── model/
│
└── frontend/ → React Vite App
├── components/
├── App.jsx
└── main.jsx


---

# 🔧 Tech Stack

## Frontend
- React (Vite)
- SockJS-client
- STOMP.js
- CSS (Custom UI)

## Backend
- Spring Boot
- Spring WebSocket
- STOMP Protocol

---

# 🔌 WebSocket Flow

### 1. Connection
Client → ws://localhost:8080/ws

### 2. Send Message
Client → /app/chat

### 3. Broadcast Message
Server → /topic/messages

### 4. Receive Message


---

# ⚙️ Backend Setup (Spring Boot)

## 1. Create Project
Use Spring Initializer:
- Maven
- Java
- Spring Boot version: 3.x / 4.x (as per system)

## 2. Dependencies
- Spring Web
- Spring WebSocket
- Spring Boot DevTools

---

## 3. Packages Structure
com.AML3B.Demo_WebSocket
├── config
├── controller
└── model

💬 How It Works
User enters username
Sends message
Message goes to Spring Boot server
Server broadcasts message
All users see message instantly

🎯 Learning Outcome
WebSocket real-time communication
STOMP protocol understanding
Full-stack integration (React + Spring Boot)
Event-driven architecture
Client-server messaging system
