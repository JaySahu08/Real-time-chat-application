# Real-Time Chat Application

A full-stack real-time chat application built using React, Spring Boot, WebSocket, STOMP, SockJS, and JWT Authentication.

This application enables users to communicate instantly through persistent WebSocket connections with secure authentication and authorization.

---

## 🚀 Features

- Real-time messaging using WebSocket
- STOMP messaging protocol integration
- JWT Authentication & Authorization
- Secure Login & Registration
- Persistent bidirectional communication
- Responsive React frontend
- Spring Boot backend APIs
- SockJS fallback support
- Protected routes and APIs

---

## 🌐 Tech Stack

### Frontend
- React.js
- STOMP.js
- SockJS
- Axios
- React Router

### Backend
- Java
- Spring Boot
- Spring Security
- Spring WebSocket
- JWT Authentication
- Maven

### Database
- MySQL

---
## 🔐 Authentication Flow

1. User registers/logs in
2. Backend generates JWT token
3. Token stored on client side
4. Protected APIs validated using JWT
5. Authenticated users connect to WebSocket server

Because apparently even sending “hello” now requires cryptographic verification. Modern software engineering remains committed to complexity.

## 🔄 WebSocket Communication Flow

```text
Client → STOMP → WebSocket → Spring Boot Server
Server → Broadcast Message → Connected Clients
```

---
