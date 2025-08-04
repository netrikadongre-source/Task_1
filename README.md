# 🚀 Node.js - Sample Web Application with CI/CD Pipeline (DevOps Internship Task 1)

This project is a sample Node.js web app built using the **Express** framework and **EJS** templates, designed for DevOps CI/CD practice.

---

## 📌 Objective

As part of **DevOps Internship Task 1**, the goal is to:
- Containerize a Node.js application using Docker
- Automate build and push process using **GitHub Actions**
- Push the Docker image to **DockerHub**

---

## 🛠 Tech Stack

- **Node.js** + Express + EJS
- **Docker**
- **GitHub Actions**
- **DockerHub**
- HTML, CSS, JavaScript (frontend)

---

## ⚙️ CI/CD Workflow (GitHub Actions)

The pipeline is defined in `.github/workflows/main.yml` and runs automatically on push to the `main` branch.

### 🔄 Steps Automated:
1. Checkout code
2. Setup Node.js environment
3. Install dependencies (`npm install`)
4. Build Docker image
5. Login to DockerHub using GitHub secrets
6. Push image to DockerHub

---

## 🐳 DockerHub Repository

➡️ Docker Image: [`netrika0210/nodejs-demo-app`](https://hub.docker.com/r/netrika0210/nodejs-demo-app)

To run the image locally:
```bash
docker pull netrika0210/nodejs-demo-app:latest
docker run -p 3000:3000 netrika0210/nodejs-demo-app
