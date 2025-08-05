# Task_02-main-flow-
A fully functional PHP-based Login &amp; Signup System with secure user authentication, password hashing, MySQL database integration, and session management. Clean, responsive HTML/CSS frontend with error handling, validation, and protected welcome page. Simple and beginner-friendly project


# 🔐 PHP Login & Signup System

A fully functional **Login & Signup System** built with **PHP, MySQL, HTML, and CSS**. It includes **secure user authentication**, **password hashing**, **error handling**, and a simple, clean UI for better user experience. 🖥️✨

---

## 🚀 Features
- 📝 User Registration (Signup)
- 🔑 Secure Login Authentication
- 🔒 Password Hashing (bcrypt)
- 📂 MySQL Database Integration
- 🚫 Error Handling & Input Validation
- 🎉 Simple Welcome Dashboard
- 🔓 Logout Functionality
- 📱 Responsive & Clean UI Design

---

## 🛠️ Tech Stack
- **PHP (Core Logic)**
- **MySQL (Database)**
- **HTML5 & CSS3 (Frontend Design)**
- **Ionicons (Icons)**

---

## 📦 Folder Structure
/project-root
├── index.php // Login Page
├── signup.php // Signup Backend Logic
├── login.php // Login Backend Logic
├── welcome.html // Protected Welcome Page
├── db.php // Database Connection
├── style.css // Login Form CSS
├── signupkrlo.css // Signup Form CSS
└── users.sql // (Optional) SQL DB Schema File


## ⚙️ Setup Instructions
1. Clone the Repository:
   ```bash
   git clone https://github.com/yourusername/your-repo-name.git
   cd your-repo-name
2.Import Database:
  Open MySQL CLI or phpMyAdmin.
  Create a database user_auth.
  Import users.sql (or create tables manually).

3.Update Database Credentials in db.php:
  $host = "localhost";
  $user = "root";
  $pass = "";  // your MySQL password
  $dbname = "user_auth";

4.Run PHP Server:
  php -S localhost:8000

5.Open Browser & Navigate:
  http://localhost:8000/index.php

🎯 Usage
Register a new account.
Login with valid credentials.
Upon success, you'll be redirected to a protected Welcome Page.
Click Logout to return to Login screen.

🤝 Contributing
Feel free to fork this repo, raise issues, and contribute with pull requests. ✨

📜 License
This project is open-source and free to use under the MIT License.

🌟 Author
Made with ❤️ by Kartik Soni 

