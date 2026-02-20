# 🍔 OrderOnTheGo – Your On-Demand Food Ordering Solution

A full-stack food ordering web application built using the MERN Stack
(MongoDB, Express.js, React.js, Node.js).

## 📌 Project Overview

OrderOnTheGo is a web-based food ordering platform that connects
customers with restaurants, enabling seamless online ordering and
efficient order management.

### 🎯 Purpose

-   Reduce customer waiting time  
-   Provide easy access to restaurant menus  
-   Enable secure online ordering  
-   Improve restaurant order management  
-   Support digital transformation of small/local food businesses

------------------------------------------------------------------------

## 🚀 Features

### 👤 Customer Features

-   User Registration & Login
-   Browse Restaurants
-   View Food Items with Prices
-   Add to Cart / Remove from Cart
-   Update Item Quantity
-   Secure Checkout
-   Order Confirmation
-   View Order History

### 🏪 Restaurant Features

-   Restaurant Login
-   Add / Update / Delete Food Items
-   View Restaurant Orders

### 🛠 Admin Features

-   Admin Login
-   Manage Users
-   Manage Restaurants
-   View All Orders

### 🔐 Security Features

-   JWT-based Authentication
-   Role-Based Access Control
-   Password Hashing using bcrypt
-   Protected API Routes
-   Input Validation & Error Handling

------------------------------------------------------------------------

## 🏗 Architecture

User (Browser) → React.js (Frontend) → Node.js + Express.js (Backend
API) → MongoDB (Database)

------------------------------------------------------------------------

## 🛠 Tech Stack

-   Frontend: React.js
-   Backend: Node.js, Express.js
-   Database: MongoDB
-   Authentication: JWT
-   Version Control: Git & GitHub

------------------------------------------------------------------------

## 📂 Project Structure

order-on-the-go/ │ ├── client/ \# React Frontend ├── server/ \# Node.js
Backend └── README.md

------------------------------------------------------------------------

## ⚙️ Setup Instructions

### 1️⃣ Clone the Repository

git clone https://github.com/shalom-m-vishal/order-on-the-go.git cd
order-on-the-go

### 2️⃣ Backend Setup

cd server npm install

Create a .env file:

PORT=5000 MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key

Start backend: npm start

### 3️⃣ Frontend Setup

cd client npm install npm run dev

------------------------------------------------------------------------

## 📡 API Base URL

http://localhost:5000/api

------------------------------------------------------------------------

## ⚠ Known Issues

-   No pagination for large datasets
-   JWT session refresh not implemented
-   No multi-factor authentication

------------------------------------------------------------------------

## 🔮 Future Enhancements

-   Pagination & Lazy Loading
-   Multi-Factor Authentication (MFA)
-   Dark Mode Support
-   Email Notifications
-   Cloud Deployment

------------------------------------------------------------------------

## 🔗 GitHub Repository

https://github.com/shalom-m-vishal/order-on-the-go.git

------------------------------------------------------------------------

## 🎥 Demo Video

https://drive.google.com/file/d/1CSk_wgEstAHhXtKUvN3XhHfs4Vn2Qs1g/view

------------------------------------------------------------------------

## 👨‍💻 Developed By

Mutti Reddy Shalom Vishal  
Sri Venkateswara College of Engineering, Tirupati

------------------------------------------------------------------------

## 🙌 Thank You
