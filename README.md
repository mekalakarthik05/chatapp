<div align="center">

# 💬 Chatty

### Modern Full Stack Real-Time Messaging Platform

Build • Connect • Communicate Instantly

![React](https://img.shields.io/badge/React-18+-61DAFB?style=for-the-badge&logo=react)
![NodeJS](https://img.shields.io/badge/Node.js-Express-339933?style=for-the-badge&logo=node.js)
![MongoDB](https://img.shields.io/badge/MongoDB-Database-47A248?style=for-the-badge&logo=mongodb)
![Socket.io](https://img.shields.io/badge/Socket.io-RealTime-black?style=for-the-badge&logo=socketdotio)
![Docker](https://img.shields.io/badge/Docker-Containerized-2496ED?style=for-the-badge&logo=docker)
![Kubernetes](https://img.shields.io/badge/Kubernetes-Ready-326CE5?style=for-the-badge&logo=kubernetes)

</div>

---

# 📖 Overview

**Chatty** is a modern full-stack real-time messaging platform designed to deliver fast, secure, and scalable communication.

Built with **React**, **Node.js**, **Express**, **MongoDB**, and **Socket.io**, Chatty enables users to exchange messages instantly while maintaining secure authentication, online presence tracking, and an intuitive user interface.

The project follows a modular architecture and includes Docker support, Kubernetes manifests, and Jenkins integration, making it suitable for both development and deployment environments.

---

# ✨ Features

### 💬 Real-Time Messaging

- Instant messaging powered by Socket.io
- Live bidirectional communication
- Automatic message synchronization

### 🔐 Secure Authentication

- JWT Authentication
- Protected API routes
- Password encryption
- Secure user sessions

### 👤 User Profiles

- User registration
- Profile management
- Profile picture upload
- Account customization

### 🟢 Online Presence

- Online/Offline indicators
- Active user tracking
- Real-time status updates

### 🎨 Responsive UI

- React
- TailwindCSS
- DaisyUI
- Mobile-friendly design

### ⚡ Production Ready

- Docker support
- Kubernetes manifests
- Jenkins CI pipeline
- Modular backend architecture

---

# 🛠 Tech Stack

| Category | Technologies |
|-----------|--------------|
| Frontend | React, TailwindCSS, DaisyUI |
| Backend | Node.js, Express.js |
| Database | MongoDB |
| Authentication | JWT |
| Real-Time | Socket.io |
| State Management | Zustand |
| DevOps | Docker, Docker Compose |
| Deployment | Kubernetes |
| CI/CD | Jenkins |

---

# 📂 Project Structure

```text
Chatty
│
├── backend/                 # Express backend & APIs
├── frontend/                # React frontend
├── k8s/                     # Kubernetes manifests
│
├── .env                     # Environment variables
├── .gitignore
├── docker-compose.yml
├── Jenkinsfile
├── package.json
└── README.md
```

---

# 🔧 Prerequisites

Install the following before running the project.

- Node.js (v18+ recommended)
- Docker
- Docker Compose
- Git
- MongoDB (for local development)

---

# ⚙ Environment Variables

Create a `.env` file in the project root.

```env
MONGODB_URI=mongodb://root:admin@mongo:27017/chatApp?authSource=admin

JWT_SECRET=your_secret_key

PORT=5001

NODE_ENV=production
```

For local development:

```env
MONGODB_URI=mongodb://localhost:27017/chatApp
```

---

# 🚀 Quick Start

Clone the repository

```bash
git clone https://github.com/mekalakarthik05/Chatty.git
```

Move into the project

```bash
cd Chatty
```

---

# 🐳 Running with Docker

Build all services

```bash
docker-compose up --build -d
```

View logs

```bash
docker-compose logs -f
```

Stop containers

```bash
docker-compose down
```

Open the application

```
http://localhost
```

---

# 💻 Local Development

## Start MongoDB

```bash
docker run -d \
-p 27017:27017 \
--name mongo \
mongo:latest
```

---

## Frontend

```bash
cd frontend

npm install

npm run dev
```

Frontend runs on

```
http://localhost:5173
```

---

## Backend

```bash
cd backend

npm install

npm run dev
```

Backend API

```
http://localhost:5001
```

---

# ☸ Kubernetes Deployment

Kubernetes manifests are available inside the **k8s/** directory.

Deploy using

```bash
kubectl apply -f k8s/
```

Check deployment status

```bash
kubectl get pods
```

---

# 🔄 CI/CD Pipeline

The project includes a **Jenkinsfile** for automated build and deployment.

Pipeline stages include:

- Source Checkout
- Dependency Installation
- Docker Image Build
- Container Deployment

---

# 📌 Repository Highlights

- 💬 Real-time WebSocket messaging
- 🔐 JWT Authentication
- 👤 Profile Management
- 🟢 Online Presence Tracking
- ⚡ Express REST APIs
- 🗄 MongoDB Integration
- 🐳 Dockerized Architecture
- ☸ Kubernetes Deployment
- 🔄 Jenkins CI/CD Pipeline

---

# 📸 Project Screenshots

## Login

```
frontend/public/login.png
```

---

## Chat

```
frontend/public/chat.png
```

---

## Settings

```
frontend/public/settings.png
```

---

## Logout

```
frontend/public/logout.png
```

---

# 🤝 Contributing

Contributions are always welcome.

You can contribute by:

- Reporting bugs
- Improving documentation
- Optimizing existing code
- Adding new features
- Opening Pull Requests

---

# 👨‍💻 Author

## Karthik Mekala

https://github.com/mekalakarthik05

If you found this project useful, consider giving it a ⭐