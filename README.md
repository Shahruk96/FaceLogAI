# 🤖 FaceLogAI

<p align="center">
  A Java + Spring Boot powered AI-driven attendance system using OpenCV (JavaCV) for real-time face recognition.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Build-Success-brightgreen" />
  <img src="https://img.shields.io/badge/SpringBoot-3.x-blue" />
  <img src="https://img.shields.io/badge/OpenCV-JavaCV-orange" />
</p>

---

## 🧠 Overview

**FaceLogAI** is an intelligent attendance system that leverages real-time face detection and recognition. Built with Java, Spring Boot, and OpenCV (via JavaCV), it enables users to capture images, train face recognition models, and mark attendance using a webcam or uploaded photos through RESTful APIs.

---

## 🚀 Tech Stack

| Technology       | Purpose                             |
|------------------|-------------------------------------|
| **Java 8+**      | Core programming language           |
| **Spring Boot**  | Backend RESTful API framework       |
| **OpenCV (JavaCV)** | Face detection and recognition    |
| **MySQL**        | Database for attendance storage     |
| **Maven**        | Build and dependency management     |
| **STS / IntelliJ** | Development IDE                   |

---

## ✨ Features

- 🎥 Real-time face recognition via webcam
- 📸 Mark attendance using uploaded images
- 🧠 Train face recognition models with HaarCascade and LBPH algorithms
- ⚠️ Prevents duplicate attendance entries per day
- 📤 Upload and manage user/menu images
- 📂 Clear training images for specific users
- 🔒 Modular and clean architecture

---

## ⚙️ API Endpoints

| Endpoint                                   | Method | Description                              |
|--------------------------------------------|--------|------------------------------------------|
| `/api/face/capture/{userId}/{numImages}`   | GET    | Capture training images for a user       |
| `/api/face/train`                          | GET    | Train the face recognition model         |
| `/api/face/mark-attendance`                | GET    | Mark attendance using webcam             |
| `/api/face/mark-attendance-from-image`     | POST   | Mark attendance from an uploaded image   |
| `/api/face/clear-images/{userId}`          | GET    | Clear training images for a user         |
| `/api/face/upload-menu-image/{userId}`     | POST   | Upload a menu image for a user           |
| `/api/face/menu-images/{userId}/view/{imageName}` | GET | View a user's uploaded menu image |

--- 


## 📦 Setup Instructions

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/scanurag/FaceLogAI.git
   cd FaceLogAI
 ---

## 🤝 Contributing

Star ⭐ the repo if you find it useful!  
Feel free to submit pull requests, report issues, or suggest improvements. 🚀

---
