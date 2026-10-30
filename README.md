<div align="center">

# 🍽️ Bistro

### Restaurant Management System

*A client-server desktop application for managing a restaurant.*

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![JavaFX](https://img.shields.io/badge/JavaFX-007396?style=for-the-badge&logo=java&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

</div>

---

## 📖 About

**Bistro** is a team project built at **Braude College of Engineering**.

A central **server** manages the business logic and the database, while a **JavaFX client** gives each type of user its own interface.

## ✨ Highlights

- 🖥️ **Client-server architecture** with a dedicated server and a desktop client
- 🎨 **JavaFX graphical interfaces** for customers, staff and administrators
- ⚙️ **Server-side controllers** that handle the business logic
- 🗄️ **MySQL database** for persistent data storage
- 🔗 **Shared module** used by both client and server

## 👥 User Roles

| 👤 Customers | 🧑‍🍳 Staff | 🛠️ Administrators |
|---|---|---|
| Dedicated customer interface | Dedicated staff interface | Dedicated administration interface |

## 🧰 Tech Stack

| | Technology |
|---|---|
| 💻 Language | Java |
| 🎨 GUI | JavaFX |
| 🗄️ Database | MySQL |
| 🌐 Architecture | Client-Server |
| 🔀 Version control | Git & GitHub |

## 🗂️ Project Structure

```
BistroProject/
├── 🖥️ BistroClient/    # JavaFX client: screens and client-side controllers
├── ⚙️ BistroServer/    # Server: business logic, controllers, database access
└── 🔗 BistroCommon/    # Shared classes used by both client and server
```

## 🚀 Getting Started

### 📋 Prerequisites

- ☕ Java Development Kit (JDK)
- 🎨 JavaFX SDK
- 🐬 MySQL Server
- 🧑‍💻 An IDE such as Eclipse or IntelliJ IDEA

### 🔧 Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/LeonSigal/BistroProject.git
   ```
2. **Open the project** in your IDE and add the JavaFX SDK to the project libraries
3. **Set up a MySQL database** and update the connection details in the server code
4. **Run the server** (`BistroServer`)
5. **Run the client** (`BistroClient`) and connect it to the server

---

<div align="center">
Made with ☕ and a lot of debugging
</div>
