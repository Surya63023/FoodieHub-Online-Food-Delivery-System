# 🍔 FoodieHub - Online Food Delivery System

A full-stack online food delivery web application built using Java Enterprise technologies. Users can browse restaurants, explore menus, add items to cart, place orders, and manage their food delivery experience through an interactive web interface.

---

## 🚀 Features

### 👤 User Management
- User Registration
- Secure User Login
- Session Management
- User Profile Handling

### 🍽 Restaurant Management
- View Available Restaurants
- Browse Restaurant Details
- Dynamic Restaurant Listings

### 📋 Menu Management
- View Restaurant Menus
- Food Item Details
- Dynamic Menu Display

### 🛒 Cart Functionality
- Add Items to Cart
- Update Quantity
- Remove Items
- Calculate Total Amount

### 📦 Order Management
- Place Orders
- Order Summary
- Order History
- Billing Information

---

## 🛠 Tech Stack

### Backend
- ☕ Java
- 🔗 JDBC
- 🌐 Servlets
- 📄 JSP

### Frontend
- 🎨 HTML5
- 🎨 CSS3
- ⚡ JavaScript

### Database
- 🗄 MySQL

### Server
- 🐱 Apache Tomcat 9

### Build Tool
- 📦 Maven

### IDE
- 💻 Eclipse IDE

### Version Control
- 🔀 Git
- 🐙 GitHub

---

## 📂 Project Structure

```text
FoodieHub_Maven
│
├── src
│   └── main
│       ├── java
│       │   └── com.food
│       │       ├── dao
│       │       ├── daoimpl
│       │       ├── model
│       │       ├── servlet
│       │       └── util
│       │
│       └── webapp
│           ├── assets
│           ├── css
│           ├── images
│           ├── js
│           ├── WEB-INF
│           └── *.jsp
│
├── pom.xml
├── README.md
└── .gitignore
```

---

## ⚙️ Database Configuration

Create a MySQL database:

```sql
CREATE DATABASE online_food_delivery;
```

Import the SQL file:

```text
online_food_delivery.sql
```

Update database credentials in:

```java
DBConnection.java
```

```java
private static final String URL =
"jdbc:mysql://localhost:3306/online_food_delivery";

private static final String USERNAME = "root";
private static final String PASSWORD = "your_password";
```

---

## 🔧 Build Project

```bash
mvn clean package
```

Generated WAR:

```text
target/FoodieHub.war
```

---

## ▶️ Run Application

Deploy:

```text
FoodieHub.war
```

into:

```text
Apache Tomcat 9
```

Open:

```text
http://localhost:8080/FoodieHub/
```

---

## 📸 Application Modules

### 🏠 Home Page
- Restaurant Listing
- Featured Food Items

### 🔐 Authentication
- Login
- Registration
- Session Handling

### 🍕 Menu Page
- Browse Food Items
- Add to Cart

### 🛒 Shopping Cart
- Quantity Management
- Price Calculation

### 📦 Order Processing
- Place Order
- Billing Summary

---

## 🎯 Learning Outcomes

This project helped me gain hands-on experience with:

- Java Web Development
- MVC Architecture
- JDBC Integration
- Session Management
- Maven Project Structure
- WAR Packaging
- Tomcat Deployment
- Git & GitHub Workflow
- Database Design

---

## 🔮 Future Enhancements

- 💳 Online Payment Gateway
- 📱 Responsive Mobile Design
- ⭐ Restaurant Ratings & Reviews
- 🔍 Advanced Search & Filters
- 📍 Live Order Tracking
- 🔔 Notifications

---

## 👨‍💻 Author

### Surya Teja

🌟 Aspiring Java Full Stack Developer

- Java
- Spring Boot
- Microservices
- React
- MySQL
- Docker
- AWS

📌 GitHub Profile:
https://github.com/Surya63023

---

## ⭐ Support

If you like this project:

⭐ Star the repository

🍴 Fork the repository

🛠 Contribute improvements

📢 Share feedback