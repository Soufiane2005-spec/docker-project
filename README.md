# 🐳 Docker Project - Containerization Platform

## 👨‍🎓 Author
Soufiane Zaakour

---

## 📌 Project Objective
Set up a Docker-based platform to deploy, manage, and orchestrate containers.

---

## 🧩 Project Tasks
- Task 1: Docker Installation
- Task 2: Nginx Deployment
- Task 3: Custom Image, Volume, Network
- Task 4: Docker Compose

---
## ⚙️ Task 1: Docker Installation

### ✔️ Description
Docker was installed on Ubuntu and configured correctly.

### 🛠️ Commands Used
```bash
sudo apt update
sudo apt install docker.io -y
sudo systemctl start docker
sudo systemctl enable docker
docker run hello-world

---
---

# ✅ 🔹 Add this for TASK 2

```markdown
## 🌐 Task 2: Nginx Deployment

### ✔️ Description
A web server was deployed using an Nginx container.

### 🛠️ Commands Used
```bash
docker pull nginx
docker run -d -p 8080:80 nginx
docker ps


