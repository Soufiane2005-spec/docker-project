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
# 🧩 Task 3 — Docker Advanced Concepts

## 🎯 Objective
Master Docker image creation, volumes, and networking.

---

## 🟦 Part A — Custom Image
- Created Dockerfile
- Built custom Nginx image
- Ran container with custom HTML page

---

## 🟩 Part B — Volumes (Persistence)

### Verification
- Docker volume created: task3-volume
- Mounted inside container at /data
- Data stored inside container
- Data persisted after container restart

### Internal storage location
/var/lib/docker/volumes/task3-volume/_data

### Result
Persistence successfully verified ✔

---

## 🟨 Part C — Networking

### Steps
- Created Docker network: task3-network
- Ran MySQL container in network
- Ran Nginx container in same network
- Verified communication using ping

### Result
Containers successfully communicated inside Docker network ✔

---

## 🧠 Key Concepts Learned
- Docker images
- Docker volumes (data persistence)
- Docker networking (container communication)
- DNS inside Docker


