<div align="center">
  <img src="image/logoHCU.png" alt="HCU Logo" width="150" height="auto" />
  <h1>HCU Vehicle License Plate Scanning & Parking System</h1>
  <p>A comprehensive parking management and vehicle registration system designed for Huachiew Chalermprakiet University (HCU).</p>
  
  [![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)](https://www.php.net/)
  [![MySQL](https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white)](https://www.mysql.com/)
  [![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
  [![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
</div>

<hr />

## 📋 Table of Contents
- [About the Project](#-about-the-project)
- [Key Features](#-key-features)
- [Roles & Access](#-roles--access)
- [Demo / Screenshots](#-demo--screenshots)
- [Project Structure](#-project-structure)
- [Installation Guide](#-installation-guide)

---

## 📖 About the Project
This project is a web-based **Parking Management System** developed to handle vehicle tracking, parking sessions, and user registration smoothly. It includes role-based access to ensure security and efficient parking management.

## ✨ Key Features
- **User Management**: Registers and manages users in different roles (Students, Staff, Executives, and Administrators).
- **Vehicle Registration**: Links user profiles with their vehicle license plates and vehicle types.
- **Parking Sessions**: Logs precise vehicle entry and exit times, recording the parking status (Parked/Completed).
- **Payment Tracking**: Allows tracking and checking of parking fee payments.
- **Role-based Dashboards**: Interactive user interfaces dedicated to each specific user role.

## 🔐 Roles & Access
1. **Admin**: Can manage the whole system, check users, payments, and view logs.
2. **Executive (Exec)**: Higher-level viewing access for reports and overview.
3. **User (Student/Staff)**: Can register their vehicles, check in/out states, and manage personal data.

---

## 📸 Demo / Screenshots

Here are some screenshots of the application in action:

### Login & Registration
![Login Screen](Demo/Screenshot%202026-03-08%20150646.png)
![Registration Screen](Demo/Screenshot%202026-03-08%20150712.png)

### User Actions & Payments
![Payment Flow 1](Demo/Screenshot%202026-03-08%20150731.png)
![Payment Flow 2](Demo/Screenshot%202026-03-08%20150743.png)
![Payment Success](Demo/Screenshot%202026-03-08%20150758.png)

### Additional Views
![View 1](Demo/Screenshot%202026-03-08%20150821.png)
![View 2](Demo/Screenshot%202026-03-08%20150837.png)

---

## 📂 Project Structure
```text
📦 Project_Y3
 ┣ 📂 image/                 # Directory containing logo and background assets
 ┣ 📜 index.html             # The landing page and role selection
 ┣ 📜 user_login.html        # User Login Page
 ┣ 📜 admin_login.html       # Admin Login Page
 ┣ 📜 admin_dashboard.php    # Admin primary dashboard
 ┣ 📜 user_dashboard.php     # Regular user dashboard
 ┣ 📜 executive_dashboard.php# Executive overview dashboard
 ┣ 📜 parking_sessions.php   # Handles active/completed parking logic
 ┣ 📜 connect.php            # Core database connection script
 ┣ 📜 style.css              # Main system stylesheets
 ┗ 📜 barrier_gate_system.sql# Database structure and sample data dump
```

## 🚀 Installation Guide
To run this project locally, follow these steps:

1. **Clone or Download** the project repository.
2. **Move** the project folder (`Project_Y3`) into your local server directory (e.g., `htdocs` for XAMPP or `www` for WAMP).
3. **Database Setup**:
   - Open `phpMyAdmin` (or your preferred MySQL client).
   - Create a new database named `barrier_gate_system`.
   - Import the provided `barrier_gate_system.sql` file into the new database.
4. **Configuration**:
   - Open `connect.php` in your code editor.
   - Verify and update the database connection credentials (`$servername`, `$username`, `$password`) if necessary.
5. **Run the Application**:
   - Open your web browser.
   - Navigate to: `http://localhost/Project_Y3/index.html` (Adjust the folder name in the URL if you renamed it).

---
<div align="center">
  <p>Built with ❤️</p>
</div>
