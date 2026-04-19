# 🚀 Project Management Backend API

A scalable and modular backend system for managing projects, tasks, and team collaboration. Built using Node.js, Express, and MongoDB with production-ready practices.

---

## 🧠 Overview

This backend API enables:

* 🔐 Secure user authentication (JWT-based)
* 📁 Project creation and management
* 👥 Team collaboration
* ✅ Task & subtask tracking
* 📝 Notes and related data handling

The architecture is designed for **scalability, maintainability, and real-world backend systems**.

---

## 🏗️ Tech Stack

* **Backend:** Node.js, Express.js
* **Database:** MongoDB (Mongoose)
* **Authentication:** JWT (Access & Refresh Tokens)
* **Security:** Helmet, CORS
* **Logging:** Morgan
* **Performance:** Compression
* **Validation:** express-validator
* **File Uploads:** Multer

---

## 📂 Project Structure

```bash
src/
 ├── controllers/        # Business logic
 ├── models/             # Database schemas
 ├── routes/             # API routes
 ├── middlewares/        # Auth, validation, multer
 ├── db/                 # Database connection
 ├── utils/              # Helpers (error, response)
 ├── validators/         # Request validation
 ├── app.js              # Express configuration
 └── index.js            # Entry point
```

---

## ⚙️ Environment Variables

Create a `.env` file:

```env
PORT=8000
MONGO_URI=your_mongodb_connection_string

CORS_ORIGIN=http://localhost:5173

ACCESS_TOKEN_SECRET=your_access_secret
ACCESS_TOKEN_EXPIRY=1d

REFRESH_TOKEN_SECRET=your_refresh_secret
REFRESH_TOKEN_EXPIRY=7d
```

---

## ▶️ Getting Started

### Install dependencies

```bash
npm install
```

### Run development server

```bash
npm run dev
```

### Run production server

```bash
npm start
```

Server runs on:

```
http://localhost:8000
```

---

## 📡 API Routes

### 🔐 Auth

* `POST /api/v1/auth/register`
* `POST /api/v1/auth/login`

### 📁 Projects

* Create project
* Manage members
* Update project details

### ✅ Tasks

* Create tasks
* Update tasks
* Manage subtasks

### ❤️ Health Check

* `GET /api/v1/healthcheck`

---

## 🧩 Key Features

* 🔐 JWT Authentication (Access & Refresh Tokens)
* 🛡️ Security middleware (Helmet, CORS)
* 📦 Modular MVC architecture
* 📄 Centralized error handling
* ⚡ Compression for performance
* 📊 Request logging (Morgan)

---

## 🧠 Architecture Highlights

* Separation of concerns (controllers, routes, models)
* Reusable middleware and utilities
* Clean and scalable folder structure
* Designed for real-world backend systems

---

## 🔮 Future Improvements

* Role-Based Access Control (RBAC)
* Redis caching
* Notifications system
* Activity logs
* Feature Flags & A/B Testing

---

## 📌 Use Cases

* Project management platforms
* Task tracking applications
* Team collaboration tools

---

## 🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first.

---

## 📬 Author

**Kranthi Kumar**
GitHub: https://github.com/kranthikumar-dev

---
