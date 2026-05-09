# Multi-Environment Application Deployment

## 📌 Overview
This project demonstrates deployment of a multi-environment ticket management application using Docker.

The application consists of:
- Frontend (React)
- Development Backend (Flask)
- Production Backend (Flask)
- MongoDB Database

---

## 🏗️ Architecture

Frontend → Backend Dev / Backend Prod → MongoDB

---

## ⚙️ Prerequisites

- Docker installed
- Docker Compose installed
- Git installed

---

## 🚀 Deployment Steps

1. Clone the repository:git clone https://github.com/RohanMangate/multienv-deployment-rohan.git
cd multienv-deployment-rohan

2. Start application: docker-compose up --build
3. Verify running containers: docker ps

---

## 🌐 Access URLs

Frontend:
http://localhost:3000

Development Environment:
http://localhost:3000/dev

Production Environment:
http://localhost:3000/prod

Direct Backend Access (optional):
http://localhost:3001  
http://localhost:3002  

---

## ✅ Features

- Multi-container Docker setup
- Separate development and production environments
- MongoDB integration
- Frontend communication with both environments

---

## 🧪 Testing

- Verified all containers using: docker ps
- Tested frontend routes:
  - /dev
  - /prod
 - Verified backend connectivity

---

## ⚠️ Assumptions

- Ports 3000, 3001, 3002 are available
- Docker is pre-installed
- Using local environment instead of EC2

---

## 🔧 Challenges Faced

- Docker networking issues
- Environment variable handling
- Connecting frontend with multiple backends

---
