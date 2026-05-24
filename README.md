# 💧 Water Resource Management System (WRMS)

## 📌 Overview

The **Water Resource Management System (WRMS)** is a software project developed to efficiently manage and monitor water resources through a digital platform. The system helps in organizing water-related data, improving resource allocation, maintaining records, and supporting better decision-making for sustainable water management.

This project focuses on providing a structured and scalable solution for handling water resource information using modern software technologies and database management concepts.

---

# 🚀 Features

- 💧 Water resource monitoring and mapping
- 📊 Data management (CRUD operations) and reporting
- 🗂️ MySQL Database integration for records
- 🔍 Search and filter functionality
- 📈 Resource analysis and tracking
- 🛠️ Modular and scalable architecture
- 📋 Efficient record management

---

# 🏗️ Tech Stack

## Frontend
- HTML
- CSS
- JavaScript

## Backend
- PHP

## Database
- MySQL

## Tools & Technologies
- Git & GitHub
- REST API / AJAX
- PDO / MySQLi

---

# 📂 Project Structure

```bash
Water-Resource-Management-System--WRMS-/
│
├── api/                   # API endpoints for frontend-backend communication
├── assets/                # CSS, Images, Icons, and Videos
├── components/            # Reusable UI components (header, footer)
├── config/                # Database configuration (db.php)
├── src/                   # Core PHP classes (River.php, Disaster.php)
├── crud_operations.php    # Central file for CRUD functions
├── index.php              # Main entry point / Dashboard
├── map.php                # Map view for resources
└── README.md              # Project documentation
```

---

# ⚙️ Installation & Setup

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/Neeljbf04/Water-Resource-Management-System--WRMS-.git
```

## 2️⃣ Navigate to Project Directory

```bash
cd Water-Resource-Management-System--WRMS-
```

## 3️⃣ Configure Database

Create a MySQL database named `project_resource`.

Update the database credentials in `config/db.php`:

```php
<?php
// config/db.php
$servername = "localhost";
$username = "root";
$password = "yourpassword";
$dbname = "project_resource";
```

*Note: You may need to import your SQL schema to initialize the tables required by the system.*

---

## 4️⃣ Run the Project

You can use XAMPP, WAMP, or PHP's built-in web server.

Using PHP's built-in server:

```bash
php -S localhost:8000
```

Then, open your browser and navigate to `http://localhost:8000/`.

---

# 🎯 Project Objectives

- Efficient water resource utilization
- Digital management of water data
- Better monitoring and analysis
- Sustainable resource planning
- Organized database management

---

# 🔮 Future Enhancements

- AI-based water prediction system
- IoT sensor integration
- Real-time monitoring dashboard
- Mobile application support
- Cloud deployment

---

# 👨‍💻 Contributors

- Neel
- Aaditya Kumar Sinha

---

# 📜 License

This project is licensed under the MIT License.

---

# 🌐 GitHub Repository

Repository Link:  
https://github.com/Neeljbf04/Water-Resource-Management-System--WRMS-
