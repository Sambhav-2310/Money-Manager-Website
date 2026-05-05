# 💰 Money Manager Application (Full Stack Personal Finance Tracker)

A production-ready **Full Stack Money Manager / Personal Finance Tracking Application** built using **Spring Boot + React.js + MySQL**, implementing secure authentication, RESTful APIs, income-expense management, and deployment-ready architecture.

This project demonstrates strong understanding of:

* Full Stack Application Development
* REST API Design & Integration
* JWT-Based Authentication
* Personal Finance & Budget Tracking
* Database Design using JPA/Hibernate
* Secure Backend Architecture
* React State Management
* Responsive UI Development
* Production Deployment (Render + Netlify)

---

# 🏗️ System Architecture

```bash id="m1n2b3"
React.js Frontend (Netlify Deployment)
        ↓
REST APIs
        ↓
Spring Boot Backend (Render Deployment)
        ↓
MySQL Database
```

---

# 🚀 Tech Stack

## 🔵 Backend

* Java 17
* Spring Boot
* Spring Security
* JWT Authentication
* Spring Data JPA (Hibernate)
* MySQL
* Maven

## 🟢 Frontend

* React.js
* Axios
* React Router
* Context API
* Bootstrap / Tailwind CSS
* React Hot Toast
* Lucide React Icons

## ☁️ Deployment

* Render (Backend)
* Netlify (Frontend)

## 🧰 Tools

* IntelliJ IDEA
* VS Code
* Postman
* MySQL Workbench
* Git & GitHub

---

# 📂 Project Structure

## 🔵 Backend Structure (Spring Boot)

```bash id="q4w5e6"
money-manager-backend/
│
├── src/main/java/com/moneymanager/
│   ├── config/
│   │   ├── SecurityConfig.java
│   │   ├── JwtFilter.java
│   │   └── CorsConfig.java
│   │
│   ├── controller/
│   │   ├── AuthController.java
│   │   ├── IncomeController.java
│   │   ├── ExpenseController.java
│   │   └── UserController.java
│   │
│   ├── service/
│   │   ├── AuthService.java
│   │   ├── IncomeService.java
│   │   ├── ExpenseService.java
│   │   └── UserService.java
│   │
│   ├── repository/
│   │   ├── UserRepository.java
│   │   ├── IncomeRepository.java
│   │   └── ExpenseRepository.java
│   │
│   ├── model/
│   │   ├── User.java
│   │   ├── Income.java
│   │   └── Expense.java
│   │
│   └── MoneyManagerApplication.java
│
├── src/main/resources/
│   ├── application.properties
│   └── data.sql
│
├── pom.xml
└── README.md
```

### Backend Design Pattern

* Layered Architecture (Controller → Service → Repository)
* JWT Stateless Authentication
* Secure REST APIs
* Role-Based Authorization
* DTO Pattern (Optional)

---

## 🟢 Frontend Structure (React.js)

```bash id="r7t8y9"
money-manager-frontend/
│
├── public/
│   └── index.html
│
├── src/
│   ├── components/
│   │   ├── Navbar.jsx
│   │   ├── Sidebar.jsx
│   │   ├── Income/
│   │   ├── Expense/
│   │   └── Auth/
│   │
│   ├── pages/
│   │   ├── Dashboard.jsx
│   │   ├── Login.jsx
│   │   ├── Register.jsx
│   │   ├── AddIncome.jsx
│   │   ├── AddExpense.jsx
│   │   └── Transactions.jsx
│   │
│   ├── services/
│   │   ├── ApiService.js
│   │   ├── AuthService.js
│   │   └── TransactionService.js
│   │
│   ├── context/
│   │   └── AppContext.jsx
│   │
│   ├── App.js
│   └── index.js
│
├── package.json
└── README.md
```

### Frontend Architecture

* Component-Based Architecture
* Protected Routes
* Global State Management with Context API
* Centralized API Layer
* Real-Time Notifications

---

# 🔐 Key Features

## ✔ Authentication & Security

* User Registration
* Secure Login
* JWT-Based Authentication
* Protected Routes
* Role-Based Access

## ✔ Income Management

* Add Income Records
* Category Selection
* Edit/Delete Income
* Income History

## ✔ Expense Management

* Add Expense Records
* Expense Categories
* Validation
* Edit/Delete Expense

## ✔ Dashboard

* Total Income Overview
* Total Expenses Overview
* Remaining Balance
* Recent Transactions
* Financial Insights

## ✔ User Experience

* Responsive UI
* Toast Notifications
* Loading Indicators
* Modern Dashboard Design

---

# 🗄️ Database Design

## Core Entities

* User
* Income
* Expense

## Relationships

```bash id="u1i2o3"
User 1 --- * Income
User 1 --- * Expense
```

---

# ⚙️ Setup Instructions

## 🖥️ Backend Setup

### 1️⃣ Create Database

```sql id="p4a5s6"
CREATE DATABASE money_manager;
```

### 2️⃣ Configure `application.properties`

```properties id="d7f8g9"
spring.datasource.url=jdbc:mysql://localhost:3306/money_manager
spring.datasource.username=root
spring.datasource.password=your_password

spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
```

### 3️⃣ Run Backend

```bash id="h1j2k3"
mvn spring-boot:run
```

### Backend URL:

```bash id="l4z5x6"
http://localhost:8080
```

---

## 🌐 Frontend Setup

### 1️⃣ Install Dependencies

```bash id="c7v8b9"
npm install
```

### 2️⃣ Run Frontend

```bash id="n1m2q3"
npm start
```

### Frontend URL:

```bash id="w4e5r6"
http://localhost:3000
```

---

# ☁️ Deployment Guide

## Backend Deployment

* Deploy Spring Boot backend on Render

## Frontend Deployment

* Deploy React frontend on Netlify

---

# 🔄 API Communication Example

```javascript id="t7y8u9"
axios.get("http://localhost:8080/api/income", {
  headers: {
    Authorization: "Bearer " + token
  }
});
```

---

# 🧪 Testing & Debugging

* Postman for API Testing
* MySQL Workbench for Database Verification
* Chrome DevTools
* Console Logs

---

# 📸 Screenshots

*Add screenshots here for:*

* Login Page
* Registration Page
* Dashboard
* Add Income
* Add Expense
* Transaction History

---

# 📈 Future Enhancements

* Monthly Budget Planning
* Financial Analytics Charts
* PDF/Excel Reports
* Recurring Payments
* Mobile App Version
* Expense Prediction AI
* Multi-user Family Finance Management

---

# 🎯 Why This Project Stands Out

* Real-world finance management use case
* Secure authentication system
* Full stack deployment-ready architecture
* Modern responsive dashboard
* Clean scalable backend design
* Resume-ready advanced project

---

# 👨‍💻 Developer

**Sambhav Gupta**
B.Tech – Information Science Engineering
Full Stack Developer | Java | Spring Boot | React

---

# ⭐ Support

If you found this project useful, consider giving it a **star** on GitHub!

---

([youtube.com][1])

[1]: https://www.youtube.com/watch?v=RtMezvuOKE0&utm_source=chatgpt.com "Build Money Manager with React + Spring Boot + MySQL ..."

