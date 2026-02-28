# MEAN Stack Application – Dockerized & CI/CD Enabled

## 📌 Overview
This project is a full-stack MEAN (MongoDB, Express, Angular, Node.js) CRUD application.
The application is containerized using Docker and deployed using Docker Compose.
CI/CD is implemented using GitHub Actions.

---

## 🏗️ Architecture
- Frontend: Angular served via Nginx (Port 80)
- Backend: Node.js + Express (Port 8080)
- Database: MongoDB 6
- CI/CD: GitHub Actions
- Container Orchestration: Docker Compose

---

## 🚀 Application Access
- Frontend: http://<VM-IP>
- Backend API: http://<VM-IP>:8080/api/tutorials

---

## 🐳 Docker Setup

### Build & Run
```bash
docker compose up -d
