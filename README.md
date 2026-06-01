# 🛒 E-Commerce Application - Full Stack MERN

![Status](https://img.shields.io/badge/status-active-success)
![Stack](https://img.shields.io/badge/stack-MERN-green)
![Auth](https://img.shields.io/badge/auth-JWT-blue)
![License](https://img.shields.io/badge/license-MIT-orange)

> A production-grade full-stack e-commerce web application built using the MERN stack, inspired by platforms like Flipkart and Amazon. Demonstrates end-to-end full stack development including authentication, product management, persistent cart system, and complete order flow.

---

## 🌐 Live Demo

🔗 [ecom-two-virid.vercel.app](https://ecom-two-virid.vercel.app/)

---

## 📌 Overview

A full-stack e-commerce platform where users can browse products, manage their cart, handle addresses, and place orders — all backed by a secure REST API with JWT authentication and MongoDB persistence.

**Key Highlights:**
- JWT-based secure authentication with protected routes
- Persistent shopping cart stored in MongoDB
- Complete order placement and checkout flow
- Address management with add, edit, and delete
- Redux-based global state management on frontend
- Modular backend architecture with MVC pattern

---

## ⚙️ Tech Stack

| Layer | Technology |
|---|---|
| Frontend | React.js, Redux, React Router, Tailwind CSS |
| Backend | Node.js, Express.js, RESTful APIs |
| Database | MongoDB, Mongoose |
| Authentication | JWT, bcrypt |
| Tools | Git, GitHub, Postman, dotenv |

---

## 🧠 Features

- ✅ User registration and login with JWT authentication
- ✅ Protected routes on both frontend and backend
- ✅ Dynamic product listing with detail pages
- ✅ Add, remove, and update quantity in cart
- ✅ Persistent cart stored in MongoDB across sessions
- ✅ Complete checkout and order placement flow
- ✅ Address management — add, edit, delete
- ✅ Redux for global state management
- ✅ Backend-driven data fetching for all product and user data
- ✅ Modular MVC backend architecture

---

## 🔗 Repositories

| Repo | Link |
|---|---|
| 🖥️ Frontend | [github.com/vaibhavkumar18/Ecom](https://github.com/vaibhavkumar18/Ecom) |
| ⚙️ Backend | [github.com/vaibhavkumar18/Ecom-backend](https://github.com/vaibhavkumar18/Ecom-backend) |

---

## 🚀 Getting Started

### Frontend Setup

#### 1. Clone Frontend Repository
```bash
git clone https://github.com/vaibhavkumar18/Ecom.git
cd Ecom
```

#### 2. Install Dependencies
```bash
npm install
```

#### 3. Setup Environment Variables
Create a `.env` file in the root:
```env
VITE_API_URL=http://localhost:3000
```

#### 4. Run Frontend
```bash
npm run dev
```

---

### Backend Setup

#### 1. Clone Backend Repository
```bash
git clone https://github.com/vaibhavkumar18/Ecom-backend.git
cd Ecom-backend
```

#### 2. Install Dependencies
```bash
npm install
```

#### 3. Setup Environment Variables
Create a `.env` file in the root:
```env
PORT=3000
MONGO_URI=your_mongodb_connection
JWT_SECRET=your_secret_key
```

#### 4. Run Backend
```bash
npm run dev
```

---

## 📡 API Reference

### Auth Routes
| Method | Endpoint | Description | Auth Required |
|---|---|---|---|
| POST | /api/auth/register | Register new user | ❌ |
| POST | /api/auth/login | Login user | ❌ |
| GET | /api/auth/get-me | Get current user | ✅ |

### Product Routes
| Method | Endpoint | Description | Auth Required |
|---|---|---|---|
| GET | /api/products | Get all products | ❌ |
| GET | /api/products/:id | Get single product | ❌ |

### Cart Routes
| Method | Endpoint | Description | Auth Required |
|---|---|---|---|
| GET | /api/cart | Get user cart | ✅ |
| POST | /api/cart/add | Add item to cart | ✅ |
| PUT | /api/cart/update | Update item quantity | ✅ |
| DELETE | /api/cart/remove/:id | Remove item from cart | ✅ |

### Order Routes
| Method | Endpoint | Description | Auth Required |
|---|---|---|---|
| POST | /api/orders/place | Place order | ✅ |
| GET | /api/orders | Get user orders | ✅ |

### Address Routes
| Method | Endpoint | Description | Auth Required |
|---|---|---|---|
| GET | /api/address | Get all addresses | ✅ |
| POST | /api/address/add | Add new address | ✅ |
| PUT | /api/address/update/:id | Update address | ✅ |
| DELETE | /api/address/delete/:id | Delete address | ✅ |

---

## 🔐 How Authentication Works

1. User registers or logs in
2. Backend signs a **JWT token** and returns it
3. Frontend stores token and sends it in every protected request
4. Auth middleware verifies token on all protected routes
5. Invalid or missing token returns 401 Unauthorized

---

## 📸 Screenshots

> Add screenshots here

---

## 👨‍💻 Author

**Vaibhav Kumar Nigam**
- 🔗 LinkedIn: [linkedin.com/in/vaibhavcodes](https://www.linkedin.com/in/vaibhavcodes)
- 🐙 GitHub: [github.com/vaibhavkumar18](https://github.com/vaibhavkumar18)
- 📧 Email: vaibhavkumarnigam30@gmail.com

---

⭐ Found this project helpful? A star would mean a lot!
