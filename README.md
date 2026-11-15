# 🎓 CampusConnect

## A Student Networking and Skill-Based Connection System

CampusConnect is a C++-based student networking and skill-based connection system developed as a college project. The project allows students to manage profiles, send connection requests, manage pending requests, and build connections with other students.

The project demonstrates the practical implementation of **Object-Oriented Programming (OOP)**, **Data Structures**, **File Handling**, **Exception Handling**, and **Modular Programming**.

---

## ✨ Features

- 👤 Student profile management
- 🔐 User authentication
- 🤝 Send connection requests
- 📥 Manage pending connection requests
- ✅ Accept connection requests
- ❌ Reject connection requests
- 🔗 Store accepted connections
- 💬 Chat functionality
- 📁 File handling for data management
- ⚠️ Exception handling for error management
- 🖥️ User-friendly frontend interface

---

## 🛠️ Technologies Used

### Backend
- **C++**
- **Object-Oriented Programming (OOP)**
- **Data Structures**
- **File Handling**
- **Exception Handling**

### Frontend
- **HTML**
- **CSS**
- **JavaScript**

### Tools
- **Git**
- **GitHub**
- **Visual Studio Code**

---

## 📂 Project Structure

```text
CampusConnect/
│
├── backend/
│   ├── Auth.cpp
│   ├── Auth.h
│   ├── CampusConnect.cpp
│   ├── CampusConnect.h
│   ├── Chat.h
│   ├── FileHandler.cpp
│   ├── FileHandler.h
│   ├── Student.cpp
│   └── Student.h
│
├── frontend/
│   ├── app.html
│   ├── app.js
│   ├── index.html
│   └── style.css
│
├── main.cpp
│
└── README.md
```

---

## 🧩 Project Modules

### 🔐 Authentication
Handles user authentication and related operations.

**Files:**
- `Auth.cpp`
- `Auth.h`

### 👤 Student Management
Handles student-related information and operations.

**Files:**
- `Student.cpp`
- `Student.h`

### 🤝 Connection Management
Handles the main logic of the CampusConnect system and student connections.

**Files:**
- `CampusConnect.cpp`
- `CampusConnect.h`

### 💬 Chat
Handles chat-related functionality.

**Files:**
- `Chat.h`

### 📁 File Handling
Handles storing and retrieving data using files.

**Files:**
- `FileHandler.cpp`
- `FileHandler.h`

### 🖥️ Frontend
Provides the user interface for interacting with the project.

**Files:**
- `app.html`
- `app.js`
- `index.html`
- `style.css`

---

## 🧠 Concepts Used

### Object-Oriented Programming

- Classes and Objects
- Encapsulation
- Constructors
- Modular Programming

### Data Structures

- **Queue** – Used for managing pending connection requests
- **Linked List** – Used for managing accepted connections

### Other Concepts

- File Handling
- Exception Handling
- Modular Programming

---

## ⚠️ Exception Handling

Exception handling is used to handle unexpected errors and prevent the program from terminating abruptly.

The project uses the C++ exception handling mechanism:

- `try`
- `throw`
- `catch`

This helps improve the reliability and robustness of the application by handling invalid or unexpected situations appropriately.

---

## 🚀 How the System Works

1. A student registers or logs into the system.
2. Student information is managed by the application.
3. Students can send connection requests to other students.
4. Pending connection requests are managed using a **Queue**.
5. A request can be **accepted** or **rejected**.
6. Accepted connections are stored using a **Linked List**.
7. File handling is used to manage and store required data.
8. Exception handling manages unexpected errors.
9. The frontend provides a user interface for interacting with the system.

---

## 💻 How to Compile and Run

### Prerequisites

Make sure you have:

- A C++ compiler such as **G++ / MinGW**
- **Visual Studio Code** or another C++ IDE
- A web browser for viewing the frontend

### Step 1: Clone the Repository

```bash
git clone https://github.com/anushkaaggarwal1203/BrainStormers-CampusConnect.git
```

### Step 2: Open the Project Folder

```bash
cd BrainStormers-CampusConnect
```

### Step 3: Compile the Backend

```bash
g++ main.cpp backend/Auth.cpp backend/CampusConnect.cpp backend/FileHandler.cpp backend/Student.cpp -o CampusConnect.exe
```


### Step 4: Run the Backend

#### On Windows

```bash
.\CampusConnect.exe
```

#### On Linux/macOS

```bash
./CampusConnect
```

---

## 🖥️ How to Run the Frontend

1. Open the `frontend` folder.
2. Open `index.html` in a web browser.

Alternatively, you can use the **Live Server extension in Visual Studio Code**.

---

## 👥 Team Contributions

### **BrainStormers**

| Team Member | Contribution |
|---|---|
| **Anushka Aggarwal** | `main.cpp`, `CampusConnect` files, project integration and testing |
| **Himanshu Prajapati** | Frontend development |
| **Kavya Patni** | Authentication and File Handler files |
| **Chetna Mehar** | Student and Chat files |

---

## 🎯 Project Objectives

- To provide a student networking system.
- To apply **Object-Oriented Programming concepts** in a practical project.
- To demonstrate the use of **Data Structures**.
- To manage connection requests efficiently.
- To implement **File Handling** for data management.
- To handle unexpected situations using **Exception Handling**.
- To demonstrate **Modular Programming** by dividing the project into separate components.
- To provide an interactive user interface through a frontend.

---

## 🔮 Future Improvements

- 🤝 Skill-based student recommendations
- 💬 Improved chat functionality
- 🔐 Enhanced authentication and security
- 🗂️ Improved data storage and management
- 🌐 Better integration between frontend and backend
- 📱 Improved responsive user interface

---

## 🎓 Project Purpose

CampusConnect was developed as a college project to demonstrate the practical implementation of:

- Object-Oriented Programming
- Data Structures
- File Handling
- Exception Handling
- Modular Programming

The project applies these concepts to create a structured student networking and skill-based connection system.

---

## 🔗 Repository

https://github.com/anushkaaggarwal1203/BrainStormers-CampusConnect

---

⭐ If you like this project, consider giving it a star!
