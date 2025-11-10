# LUMO
Lumo is a foundational real-time chat and collaboration application, built to demonstrate seamless, low-latency communication between users. Designed as a proof-of-concept for a platform similar to Slack, Lumo allows users to connect instantly, join different channels, and engage in continuous conversation.

This is the initial version of the project, created to explore and implement core full-stack and real-time technologies.

---
### Live Deployment
Hosted on netlify and render : https://chatlumo.netlify.app/

---
### Key Features
**1. Instant Real-Time Messaging:** Utilizes Socket.io (WebSockets) for reliable, instant message delivery between users.

**2. Secure User Authentication:** Implements a robust login/registration flow using JWT (JSON Web Tokens) for secure session management.

**3. Dedicated Channels:** Organize conversations into multiple distinct chat channels or rooms.

**4. Persistent Chat History:** Messages are stored in MongoDB and loaded instantly when a user joins a channel.

**5. Bootstrap Styling:** A clean, mobile-responsive user interface thanks to Bootstrap CSS.

---
### Tech Stack
Lumo is a MERN-stack application with real-time capabilities:

| Component | Technology | Role in Lumo |
| :--- | :--- | :--- |
| **Frontend** | React.js | Library for building the dynamic, component-based user interface. |
| **Styling** | Bootstrap CSS | Provides pre-designed components and a responsive layout system. |
| **Real-time** | WebSockets (Socket.io) | Handles the instant, bidirectional communication required for chat. |
| **Backend** | Node.js / Express.js | High-performance runtime and framework for the RESTful API and WebSocket server. |
| **Database** | MongoDB & Mongoose | Flexible NoSQL database for storing user data, messages, and channel information. |
| **Security** | JWT Authentication | Secures API endpoints and manages user sessions efficiently. |
| **Configuration** | CORS | Configured to allow secure cross-origin communication between the client and server. |

---
### Future Enhancements 
While this is the initial version, there's significant potential for growth. Future improvements could include:

**1. Direct Messaging (DMs):** Private 1:1 chat functionality.

**2. Typing Indicators:** Displaying when other users are actively typing.

**3. File Sharing:** Allowing users to upload and share images or documents.

**4. User Roles:** Implementing Admin and standard user roles.

---
This README provides an overview of LUMO, including the description of tech stack required for it. It aims to be informative for viewers and collaborators referring to this repository.
