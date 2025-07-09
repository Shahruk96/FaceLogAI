# 🤖 FaceLogAI

<p align="center">
  A Java + Spring Boot powered AI-driven attendance system using OpenCV (JavaCV) for real-time face recognition.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Build-Success-brightgreen" />
  <img src="https://img.shields.io/badge/SpringBoot-3.x-blue" />
  <img src="https://img.shields.io/badge/OpenCV-JavaCV-orange" />
  <img src="https://img.shields.io/badge/License-MIT-green" />
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

## 📦 Setup Instructions

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/<your-username>/FaceLogAI.git
   cd FaceLogAI
