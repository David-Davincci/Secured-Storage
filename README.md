# File Sharing Web App (ReactJS, Node.js, MongoDB)

A complete file‑sharing application built from scratch using **ReactJS**, **Node.js (Express 4)**, and **MongoDB**, with features like S3 upload/download, ZIP archiving, email sending, and user authentication.

---
[Here's the Complete Guide to Build a Fast & Secure File Sharing App with AWS S3, React, & NodeJs.](https://www.sevensquaretech.com/fast-secure-file-sharing-app-aws-s3-react-nodejs-github-code/)

## 🚀 Features

### Part 1: Express 4 Node.js Backend Setup

- REST API created using Express 4
- MongoDB connection setup
- Environment variables & configuration

### Part 2: Create React App

- React project initialized
- Component structure setup
- UI screens for upload, download, login

### Part 3: Connect React with API Backend

- Axios integration
- File upload & download API communication

### Part 4: React Router

- Multi‑page navigation
- Pages: Upload, Download, Login, Dashboard

### Part 5: Node Archiver – ZIP File Creation

- Backend ZIP creation using `archiver`
- Multi‑file download support

### Part 6: Send Email with Node.js

- Email service using Nodemailer
- Share file link via email

### Part 7: Amazon S3 Upload

- File upload to AWS S3 bucket
- S3 SDK integration

### Part 8: Amazon S3 File Download

- Generate secure S3 download URLs
- Handle search & file retrieval

### Part 9: User Login Form

- Login page in React
- JWT authentication in backend

---

## 📦 Installation

```bash
cd fileapp/api
npm install
```

---

## 🔧 Development (Backend)

```bash
npm run dev
```

---

## ▶️ Start React App

```bash
cd app
npm start
```

---

## 📁 Project Structure (Basic)

```
fileapp/
│── api/        → Node.js backend
│── app/        → React frontend
└── README.md
```

---

## 📝 Notes

- Make sure to create a `.env` file in the backend for MongoDB, JWT, and S3 keys.
- Ensure CORS is enabled for API communication.

---

Happy Coding!
