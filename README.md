# 🕵️‍♂️ Contactless Attendance System

This is a secure, multi-tenant, face and location-based **attendance system** designed to replace traditional biometric systems. It leverages **face recognition**, **GPS location**, **JWT authentication**, and a hybrid database setup using **MySQL** and **MongoDB**.

---

## 🚀 Features

- 🔐 **JWT Authentication** for secure login
- 👨‍💼 **Multi-Tenant Support** (companies using a shared platform)
- 🧠 **On-Device Face Recognition** with optional image hashing
- 📍 **GPS Validation** to ensure physical presence
- 🧾 **Attendance Logging** stored in MongoDB for scalability
- 📊 **User and Tenant Management** stored in MySQL
- 🛡️ Basic **liveness detection** using image hashes

---

## 🧱 Tech Stack

| Layer | Technology |
|-------|------------|
| Frontend | [Ionic React](https://ionicframework.com/react) |
| Backend | Node.js + Express.js |
| Authentication | JSON Web Tokens (JWT) |
| SQL DB | MySQL (for users & tenants) |
| NoSQL DB | MongoDB (for attendance records) |
| Face Recognition | On-device via Capacitor Camera |
| Location | Capacitor Geolocation Plugin |