# 🏦 GenBank - Bank Management System

A secure and user-friendly **Bank Management System** developed using **Java, Spring Boot, MySQL, and Thymeleaf**. The application provides OTP-based account registration, secure authentication, account management, and separate dashboards for users and administrators.

---

## 📌 Project Overview

GenBank is a web-based banking application designed to simplify banking operations through a secure and efficient system. The project follows the **Spring Boot MVC architecture** and integrates a **Python-based OTP service** for user verification during registration.

The application enables users to create bank accounts, securely log in, manage their profiles, and perform banking-related operations, while administrators can manage users and monitor system activities.

---

## 🚀 Features

### User Module
- User Registration
- OTP Verification
- Secure Login
- Profile Management
- Account Information
- Balance Display
- Change Password

### Admin Module
- Admin Login
- View All Customers
- Manage Customer Accounts
- Dashboard

### Security Features
- OTP-Based Email Verification
- Password Authentication
- Session Management

---

## 🛠️ Tech Stack

### Backend
- Java 17
- Spring Boot
- Spring MVC
- Spring Data JPA
- Hibernate

### Frontend
- HTML5
- CSS3
- Bootstrap
- Thymeleaf

### Database
- MySQL

### Other Tools
- Maven
- Git
- GitHub
- Python (OTP Service)

---

## 📂 Project Structure

```
GenBank-Project
│
├── src
│   ├── main
│   │   ├── java
│   │   │   ├── controller
│   │   │   ├── service
│   │   │   ├── repository
│   │   │   ├── model
│   │   │   └── configuration
│   │   │
│   │   ├── resources
│   │   │   ├── templates
│   │   │   ├── static
│   │   │   └── application.properties
│   │
│   └── test
│
├── pom.xml
└── README.md
```

---

## 🗄️ Database Design

### Main Tables

- User
- Admin

### Technologies Used

- MySQL Database
- Spring Data JPA
- Hibernate ORM

---

## 🔄 Application Workflow

```
User
   │
   ▼
Registration
   │
   ▼
OTP Verification
   │
   ▼
Account Creation
   │
   ▼
Login
   │
   ▼
Dashboard
```

---

## 🏗️ Architecture

```
User Interface (Thymeleaf)
          │
          ▼
Spring MVC Controller
          │
          ▼
Service Layer
          │
          ▼
Repository (JPA)
          │
          ▼
MySQL Database
```

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/yourusername/GenBank-Project.git
```

### Open Project

Open the project using:

- IntelliJ IDEA
- Eclipse
- Spring Tool Suite (STS)

### Configure Database

Create a MySQL database.

Example:

```sql
CREATE DATABASE genbank_db;
```

Update the database credentials in:

```
src/main/resources/application.properties
```

Example:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/genbank_db
spring.datasource.username=root
spring.datasource.password=yourpassword

spring.jpa.hibernate.ddl-auto=update
```

---

## ▶️ Run Project

Run the Spring Boot application.

Open:

```
http://localhost:8080
```

---

## 📸 Screenshots

Add screenshots of:

- Home Page
- Registration Page
- Login Page
- User Dashboard
- Admin Dashboard

---

## 💡 Future Enhancements

- Money Transfer
- Transaction History
- Loan Management
- Fixed Deposit Module
- ATM Card Management
- SMS Notifications
- Email Notifications
- Statement Download (PDF)
- Admin Reports
- Role-Based Authentication

---

## 🎯 Learning Outcomes

Through this project I learned:

- Spring Boot MVC Architecture
- Spring Data JPA
- Hibernate ORM
- REST API Integration
- MySQL Database Design
- Authentication & Authorization
- Session Management
- Git & GitHub
- Backend Development Best Practices

---

## 📚 Skills Demonstrated

- Java
- Spring Boot
- Spring MVC
- Hibernate
- Spring Data JPA
- MySQL
- SQL
- HTML
- CSS
- Bootstrap
- REST API
- Git
- GitHub

---








