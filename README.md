# 🚀 DevOps CI/CD Project

### Node.js • Docker • AWS EC2 • Nginx

---

## 🌐 Live Application

🔗 http://3.110.37.157

---

## 📌 Project Overview

A containerized Node.js application deployed on AWS EC2 using Docker, with Nginx configured as a reverse proxy to serve the application on port 80.

---

## ⚙️ What’s Implemented

### 🟢 Application Layer

* Node.js application built with Express
* Routes implemented:

  * `/` → main endpoint
  * `/health` → health check
* Server configured on port **3000**

---

### 🔵 Version Control

* Git initialized
* `.gitignore` configured
* Code pushed to GitHub

---

### 🟡 Containerization

* Dockerfile created
* Image built locally
* Container executed with port mapping (`3000:3000`)
* Application verified inside container

---

### 🟣 Container Registry

* Image tagged properly
* Pushed to Docker Hub
* Pulled and executed from Docker Hub

---

### 🔴 Cloud Deployment

* AWS EC2 instance (Ubuntu) launched
* SSH access configured
* Docker installed on server
* Container deployed using Docker image
* Application exposed via public IP

---

### ⚫ Reverse Proxy (Production Layer)

* Nginx installed and configured
* Reverse proxy setup:

  * **Port 80 → Port 3000**
* Application accessible without specifying port

---

## 🏗️ Architecture

```
User Request
     ↓
Nginx (Port 80)
     ↓
Docker Container (Node.js App - Port 3000)
     ↓
AWS EC2 Instance
```

---

## 🧰 Tech Stack

| Category        | Tools Used       |
| --------------- | ---------------- |
| Backend         | Node.js, Express |
| Container       | Docker           |
| Cloud           | AWS EC2          |
| Web Server      | Nginx            |
| Version Control | Git, GitHub      |

---

## 📦 Key Highlights

* Containerized application using Docker
* Deployed on cloud infrastructure (AWS EC2)
* Reverse proxy setup using Nginx
* Clean URL access via port 80
* End-to-end deployment workflow implemented

---

## 🔜 Next Step

* CI/CD pipeline using GitHub Actions

---
