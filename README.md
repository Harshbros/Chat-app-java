# Employee Chat App (Java)

A secure internal chat application written in Java using socket programming. It enables real-time communication exclusively between authenticated employees in an organization.

##  Key Features

- **Employee-only login**: Authentication using predefined credentials
- **Real-time messaging**: TCP socket-based chat with multi-client support
- **Multi-threaded server**: Handles multiple concurrent clients
- **Simple terminal-based interface**
- **Broadcast system**: Messages are shared with all connected users

## 📁 Project Structure

EmployeeChatApp/ ├── server/ │ 
└── ChatServer.java # Listens for connections and handles broadcasting 
├── client/ │ └── ChatClient.java # Connects to server and sends/receives messages
├── auth/ │ └── EmployeeAuth.java # Validates employee credentials (local logic or file)
├── model/ │ └── User.java 
