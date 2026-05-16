# Real-Time Full-Stack Notification System

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![React](https://img.shields.io/badge/React-18.x-61DAFB?logo=react)
![Node.js](https://img.shields.io/badge/Node.js-18.x-339933?logo=node.js)
![Express](https://img.shields.io/badge/Express-4.x-000000?logo=express)
![Socket.io](https://img.shields.io/badge/Socket.io-4.x-010101?logo=socket.io)

A comprehensive, production-ready notification system featuring real-time updates, a scalable architecture, and a detailed system design roadmap. This project demonstrates full-stack development best practices, from basic API implementation to advanced performance optimization and priority-based delivery.

---

## 📸 Project Visuals

<p align="center">
  <img src="screenshots/desktop_view.png" alt="Desktop View" width="700"/>
  <br>
  <em>Main Dashboard Interface</em>
</p>

<p align="center">
  <img src="screenshots/mobile_view.png" alt="Mobile View" width="300"/>
  <br>
  <em>Mobile Responsive View</em>
</p>

---

## ✨ Key Features

- **Real-Time Delivery**: Instant notifications powered by WebSockets (Socket.IO).
- **Scalable Backend**: RESTful API built with Node.js and Express.
- **Modern Frontend**: Interactive UI built with React, Vite, and Material UI (MUI).
- **Logging Middleware**: Dedicated middleware for request tracking and monitoring.
- **System Design Roadmap**: A deep dive into database optimization, indexing, and high-availability architecture.
- **Priority Inbox**: Algorithmic sorting of notifications based on type and recency.

---

## 🛠️ Tech Stack

### Frontend
- **React 18** (Vite)
- **Material UI (MUI)** for professional styling
- **Axios** for API communication
- **Socket.io-client** for real-time events

### Backend
- **Node.js** (ES Modules)
- **Express.js**
- **Socket.io** for WebSocket orchestration
- **CORS** enabled for cross-origin security

### Middleware & Tools
- **Custom Logging Middleware**: Located in `/logging_middleware`.
- **System Design Documentation**: Detailed in `notification_system_design.md`.

---

## 📂 Project Structure

```text
fullstack_submission/
├── notification_app_fe/    # React Frontend (Vite)
├── notification_app_be/    # Node.js Express Backend
├── logging_middleware/     # Custom logging logic
├── screenshots/            # UI Preview images
└── notification_system_design.md  # Detailed engineering design
```

---

## 🚀 Getting Started

### Prerequisites
- Node.js (v18 or higher)
- npm or yarn

### 1. Setup Backend
```bash
cd notification_app_be
npm install
npm start
```
*The server will start on port 3001 by default.*

### 2. Setup Frontend
```bash
cd notification_app_fe
npm install
npm run dev
```
*The application will be available at http://localhost:5173.*

---

## 🧠 System Design Insights

This project includes a comprehensive engineering document (`notification_system_design.md`) that covers:

1.  **Stage 1-2**: Basic API design and Database Schema (PostgreSQL).
2.  **Stage 3**: Slow query analysis and Composite Indexing.
3.  **Stage 4**: Performance improvements using Redis Caching and CDNs.
4.  **Stage 5**: Transitioning to an Event-Driven Architecture (Kafka/RabbitMQ).
5.  **Stage 6**: Implementing a Priority Inbox using Min-Heaps for efficient sorting.

---

## 📜 License

This project is licensed under the MIT License - see the LICENSE file for details.

---

<p align="center">Made with ❤️ for Scalable Engineering</p>
