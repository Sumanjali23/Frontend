# 🎨 Frontend — React + TypeScript LMS UI

> A modern React + TypeScript frontend for the Learning Management System, containerised with Docker and served via Nginx.

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)

---

## 📌 Overview

This is the **React TypeScript frontend** for the Learning Management System. It communicates with the Flask backend API and provides interfaces for both students and teachers to manage courses, assignments, and grades.

---

## ✨ Features

- 👩‍🎓 Student & teacher dashboards
- 📚 Course browsing and enrollment
- 📝 Assignment submission interface
- 🏆 Grade viewing
- 🎨 Styled with Tailwind CSS
- 🐳 Dockerised with Nginx for production serving

---

## 🚀 Getting Started

### Run Locally
```bash
npm install
npm start
```
Opens at `http://localhost:3000`

### Available Scripts

| Command | Description |
|---|---|
| `npm start` | Run in development mode |
| `npm test` | Launch test runner |
| `npm run build` | Build for production |

### Run with Docker
```bash
docker build -t lms-frontend .
docker run -p 3000:80 lms-frontend
```

📦 Frontend
┣ 📂 public/
┣ 📂 src/
┣ 📄 Dockerfile
┣ 📄 nginx.conf
┣ 📄 tailwind.config.js
┣ 📄 tsconfig.json
┗ 📄 package.json

---

## 🔗 Related

- 🔧 [Backend API](https://github.com/Sumanjali23/Backend-)

---

<p align="center">Made with ⚛️ by <a href="https://github.com/Sumanjali23">Grace Sumanjali Pagolu</a></p>
---

## 📁 Project Structure
