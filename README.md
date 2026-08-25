# 🐳 Dockerized Flask Application

A simple Flask web application containerized using Docker and published to Docker Hub.

This project demonstrates the basic DevOps workflow of developing a Flask application, creating a Docker image, running the application inside a Docker container, and publishing the image to Docker Hub.

---

## 📌 Project Description

This project is a simple Python Flask web application that displays a message in the browser.

The application is packaged inside a Docker container using a lightweight Python 3.12 image.

The Docker image is published on Docker Hub so that anyone can pull and run the application without installing Python or Flask manually.

---

## ✨ Features

- Simple Python Flask web application
- Dockerized Flask application
- Lightweight Python 3.12 Slim base image
- Dependency installation using `requirements.txt`
- Docker image published to Docker Hub
- Easy application deployment
- Easy container management
- GitHub-based source code management
- Ready for GitHub Actions CI/CD

---

## 🏗️ Architecture

The application follows this workflow:

```text
Developer
    │
    ▼
GitHub Repository
    │
    ▼
Flask Application
    │
    ▼
Dockerfile
    │
    ▼
Docker Build
    │
    ▼
Docker Image
    │
    ▼
Docker Hub
    │
    ▼
Docker Container
    │
    ▼
Flask Application
    │
    ▼
Browser
    │
    ▼
http://localhost:5000

🛠️ Technologies Used
Technology	Purpose
Python	Application programming language
Flask	Web application framework
Docker	Application containerization
Docker Hub	Docker image registry
Git	Version control
GitHub	Source code repository
PowerShell	Command-line operations

