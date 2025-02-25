# Courier Management System

## 📌 Project Overview
The **Courier Management System (CMS)** is an online platform designed to manage courier services efficiently. It allows users to book shipments, track deliveries, and manage logistics operations, reducing manual effort and improving coordination between branches.

---

## 📋 Features
### 🏢 **Admin Features**
- Manage **branches** and **users**
- Assign **routes** for shipments
- View **real-time reports** on bookings, deliveries, and logistics

### 📦 **User Features**
- **Book shipments** with source, destination, and package details
- **Track shipments** in real-time
- **View transaction history**

---

## ⚙️ Technology Stack
- **Frontend:** HTML, CSS, Bootstrap
- **Backend:** PHP
- **Database:** MySQL
- **Hosting:** Windows XP Professional

---

## 🚀 Installation & Setup
### Prerequisites
Ensure you have the following installed:
- PHP
- MySQL
- Web Server (e.g., XAMPP, WAMP)

### Steps to Install
1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-repository/courier-management.git
   ```
2. **Move Files to Server Directory**
   Place the project folder inside the `htdocs` (XAMPP) or `www` (WAMP) directory.

3. **Create Database**
   - Open MySQL and create a new database:
     ```sql
     CREATE DATABASE courier_management;
     ```
   - Import the provided SQL file into MySQL.

4. **Configure Database Connection**
   - Open `config.php` and update the database credentials:
     ```php
     $host = "localhost";
     $user = "root";
     $password = "";
     $database = "courier_management";
     ```

5. **Run the Application**
   - Start Apache & MySQL in XAMPP/WAMP.
   - Open a browser and go to:
     ```
     http://localhost/courier-management
     ```

---

## 📖 Usage Instructions
- **Admin Login**: Access the admin panel to manage branches, users, and logistics.
- **User Registration & Booking**: Users can sign up, book shipments, and track them.

---

## 🛠 Future Enhancements
- **Online Payment Integration**
- **AI-Based Route Optimization**
- **Mobile App Development**
- **Cloud Deployment for Scalability**

---

## 📝 Contributors
- **Amit Kumar Mishra**  
- **Ankan Nayak**  
- **Gorantla Maheswar**  
