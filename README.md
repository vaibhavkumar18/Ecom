# 🛒 Full Stack E-Commerce Application (MERN)

A production-style **E-Commerce Web App** built using the **MERN stack**, inspired by platforms like Flipkart and Amazon.

This project demonstrates **end-to-end full stack development**, including authentication, product management, cart handling, and order flow.

---

## 📌 Overview

This application allows users to:
- Browse products
- Add/remove items from cart
- Manage user accounts
- Place orders (basic flow)
- Store and fetch data from a backend database

Built with a focus on **scalable architecture and real-world backend practices**.

---

## ⚙️ Tech Stack

### 🖥️ Frontend
- React.js (Hooks)
- Redux (State Management)
- Tailwind CSS
- React Router

### 🌐 Backend
- Node.js
- Express.js

### 🗄️ Database
- MongoDB
- Mongoose

### 🔐 Authentication
- JWT (JSON Web Tokens)

---

## 🧠 Features

### 👤 Authentication
- User Signup & Login
- JWT-based authentication
- Protected routes

### 🛍️ Product System
- Dynamic product listing
- Product detail pages
- Backend-driven data

### 🛒 Cart System
- Add to cart
- Remove from cart
- Update quantity
- Persistent cart (stored in database)

### 📦 Order Flow
- Basic checkout process
- Order placement logic

### 📍 Address Management
- Add / Edit / Delete address
- Redux-based state handling

---

## 🏗️ Architecture

- Separation of frontend and backend
- RESTful API design
- Modular backend structure (routes, controllers, models)
- Centralized state management using Redux

---

## 📁 Project Structure
client/
├── components/
├── pages/
├── redux/
└── App.jsx

server/
├── controllers/
├── routes/
├── models/
└── server.js


---

## 🚀 Getting Started

### 1. Clone Repository
```bash
git clone https://github.com/your-username/ecommerce-app.git
cd ecommerce-app
```
### 2. Install Dependencies
```
# frontend
cd client
npm install
```
```
# backend
cd ../server
npm install 
```
### 3. Environment Variables
#### Create a .env file in the server folder:
```
PORT=5000
MONGO_URI=your_mongodb_connection
JWT_SECRET=your_secret_key
```

### 4. Run Application

```
# backend
npx nodemon user.js
```
```
# frontend
npm run dev
```
