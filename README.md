# campswap_Campus-Marketplace-Student-to-Student-Reselling-Platform
**CampSwap** is a student-focused second-hand marketplace designed for university campuses. It allows verified students to **buy and sell new or pre-owned products within their campus**, making transactions easier, safer, and more convenient. 
 **CampSwap**
--------------------------------------------------------
### A Student-to-Student Campus Marketplace 🛒

 **CampSwap** is a **campus-exclusive second-hand marketplace** designed for university students. It provides a platform where students can **buy and sell new or pre-owned products within their university campus**.
-----------------------------------------
## 📌 Project Overview

Students often have books, electronics, sports equipment, furniture, accessories, and other useful items that they no longer need.

Traditional marketplaces can make it difficult to find trusted buyers or sellers nearby.

** **CampSwap** solves this problem by creating a dedicated marketplace for students within a university campus.**

Students can list their products, browse available products, communicate with sellers, and complete transactions within the campus.

---

## ✨ Features

### 👤 Student Features

* 🔐 Student Registration & Login
* 👤 Student Profile
* 🛍️ Create Product Listings
* 📸 Upload Product Images
* 💰 Set Product Price
* 🔍 Search Products
* 🗂️ Browse by Categories
* 🎯 Filter Products
* ❤️ Add Products to Wishlist
* 💬 Buyer-Seller Chat
* 📦 Manage Listed Products
* ✅ Mark Products as Sold
* ⭐ Rate & Review Sellers
* 🚨 Report Products or Users

### 👨‍💼 Admin Features

* 📊 Admin Dashboard
* 👥 Manage Students
* 🛍️ Manage Product Listings
* 🚨 Manage Reports
* 🚫 Block/Unblock Users
* 🗑️ Remove Inappropriate Listings
* 📈 View Marketplace Statistics
* 🗂️ Manage Product Categories

---

## 🛒 How It Works

```text
Student Registration
        ↓
   Student Login
        ↓
 ┌──────┴──────┐
 ↓             ↓
BUY           SELL
 ↓             ↓
Browse        Add Product
Products      ↓
 ↓            Upload Images
Search        ↓
 ↓            Set Price
Filter        ↓
 ↓            Publish
View Product  ↓
 ↓            Buyer Contacts Seller
 └──────┬──────┘
        ↓
   Campus Transaction
        ↓
   Rating & Review
```

---

## 🛠️ Technology Stack

### Frontend

* HTML
* CSS
* JavaScript
* React.js

### Backend

* Node.js
* Express.js

### Database

* MySQL

### Authentication

* JWT Authentication

### Other Technologies

* REST APIs
* Cloud Image Storage
* Git & GitHub

---

## 🗄️ Main Database Entities

The system can contain the following entities:

* **Users**
* **Products**
* **Categories**
* **Messages**
* **Wishlist**
* **Reviews**
* **Reports**
* **Transactions**

---

## 📂 Project Structure

```text
Campswap/
│
├── frontend/
│   ├── src/
│   ├── public/
│   └── package.json
│
├── backend/
│   ├── routes/
│   ├── controllers/
│   ├── models/
│   ├── middleware/
│   └── server.js
│
├── database/
│   └── campswap.sql
│
├── screenshots/
│
├── .gitignore
└── README.md
```

---

## ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/CampSwap.git
```

### 2. Navigate to the Project

```bash
cd CampSwap
```

### 3. Install Frontend Dependencies

```bash
cd frontend
npm install
```

### 4. Install Backend Dependencies

```bash
cd ../backend
npm install
```

### 5. Configure Environment Variables

Create a `.env` file inside the backend folder:

```env
PORT=5000
DB_HOST=localhost
DB_USER=root
DB_PASSWORD=your_password
DB_NAME=campSwap
JWT_SECRET=your_secret_key
```

### 6. Setup Database

Create a MySQL database:

```sql
CREATE DATABASE campswap;
```

Import the provided SQL file into the database.

### 7. Start Backend

```bash
npm start
```

### 8. Start Frontend

Open another terminal:

```bash
cd frontend
npm run dev
```

---

## 📸 Screenshots

Screenshots of the application will be added here after the UI is completed.

### 🏠 Home Page

> Add screenshot here

### 🛍️ Product Listing

> Add screenshot here

### 👤 Student Profile

> Add screenshot here

### 💬 Chat

> Add screenshot here

### 👨‍💼 Admin Dashboard

> Add screenshot here

---

## 🎯 Project Objectives

1. Create a dedicated marketplace for university students.
2. Make buying and selling second-hand products easier.
3. Reduce the difficulty of finding nearby buyers and sellers.
4. Encourage reuse of products among students.
5. Provide a convenient and campus-focused trading platform.
6. Create a safer environment through student authentication.
7. Develop a practical full-stack web application.

---

## 🚀 Future Scope

Future versions of  **CampSwap** can include:

* 📱 Android/iOS mobile application
* 💳 Online payment integration
* 📍 Campus location-based product discovery
* 🔔 Real-time notifications
* 🤖 AI-powered product recommendations
* 🧠 AI-based price suggestions
* 🔐 College email verification
* 📦 Transaction tracking
* 🏫 Support for multiple universities
* 📊 Advanced analytics

---

## 🔒 Security(upcoming)

The application aims to protect user data through:

* Secure authentication
* Password hashing
* JWT-based authorization
* Input validation
* Protected API routes
* Role-based access control
* User reporting and moderation

---

## 🎓 Academic Project

**Project Name:** CampSwap
**Project Type:** Major Project
**Domain:** Full-Stack Web Development
**Target Users:** University Students

---

## 👨‍💻 Contributors

**Omkar Laygude**
**Chaitanya Lande**

BCA Student
JSPM's JIMS, Pune

---

## ⭐ Support

If you find this project interesting, consider giving the repository a ⭐ on GitHub!

---

### 📜 License

This project is developed for **educational and academic purposes**.
