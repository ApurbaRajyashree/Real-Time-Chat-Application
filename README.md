# Real-Time-Chat-Application
This project is a real-time chat application built using Spring Boot, WebSocket, STOMP, SockJS, and Thymeleaf. It demonstrates how to implement real-time communication between multiple clients using WebSocket messaging in a Spring Boot application.

**🚀 Features**
---------------
⚡ Real-time messaging
🔗 WebSocket communication
📡 STOMP messaging protocol
🌐 SockJS fallback for browser compatibility
🎨 Simple UI with Bootstrap
🖥️ Server-side rendering using Thymeleaf
📬 Broadcast messaging to all connected users

**🛠 Tech Stack**
**Backend**: Java 25, Spring Boot, Spring Web MVC, Spring WebSocket, STOMP Messaging
**Frontend**: HTML, Thymeleaf, Bootstrap 5, JavaScript, SockJS, STOMP.js
**Build Tool**: Maven

**📂 Project Structure**
src
 ├── main
 │   ├── java/com/chat/app
 │   │   ├── config
 │   │   │    └── WebSocketConfig.java
 │   │   ├── controller
 │   │   │    └── ChatController.java
 │   │   ├── model
 │   │   │    └── ChatMessage.java
 │   │   └── AppApplication.java
 │   │
 │   └── resources
 │        ├── templates
 │        │     └── chat.html
 │        └── application.properties

📚** Learning Outcomes**
This project demonstrates:
Implementation of WebSockets in Spring Boot
Using STOMP protocol for messaging
Real-time event-driven architecture
Integration of frontend WebSocket clients with a Spring backend

🔮** Future Improvements**
👤 User authentication (Spring Security)
💾 Chat history stored in a database
💬 Private messaging between users
🟢 Online/offline user status
📱 Responsive UI improvements

 
