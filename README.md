# 🍔 Full Stack Food Delivery App

A **production-like full stack food delivery web application** built using modern technologies with **real-time tracking, multi-role authentication, and complete order lifecycle management**.

---

## 🚀 Features

### 👤 User Features

* Signup & Login (JWT Authentication 🔐)
* Browse Restaurants & Menu 🍽️
* Add to Cart & Place Orders 🛒
* View Order History 📦
* Real-time Order Status Updates ⚡
* Live Delivery Tracking (Map Simulation 🗺️)

---

### 🧑‍💼 Admin Features

* View all orders
* Update order status:

  * Pending → Preparing → Out for Delivery → Delivered
* Real-time status broadcasting using WebSockets

---

### 🚴 Delivery Partner Features

* Separate login system
* View assigned orders
* Update delivery status
* Role-based access control

---

### 💳 Payment System

* Simulated payment gateway
* Handles:

  * Success ✅
  * Failure ❌
* Stores transaction details in database

---

## ⚡ Real-Time Functionality

* Built using **Socket.IO**
* Instant order updates without page refresh
* Event-driven architecture:

  * `order_update` events
  * User-specific rooms

---

## 🗺️ Live Delivery Tracking

* Map-based simulation using Leaflet
* Dynamic delivery movement
* Activated when order is **Out for Delivery**

---

## 🧱 Tech Stack

### Frontend

* React
* Axios
* React Router

### Backend

* Node.js
* Express.js
* Socket.IO

### Database

* MySQL

### Others

* JWT (Authentication)
* bcrypt (Password hashing)
* dotenv (Environment variables)

---

## 🗄️ Database Schema

* Users
* Restaurants
* Menu
* Orders
* Order_Items
* Delivery
* Reviews
* Payments
* Delivery_Partners

✔ Fully normalized (3NF)
✔ Optimized using indexing

---

## 🔐 Authentication

* JWT-based authentication
* Role-based access:

  * User
  * Admin
  * Delivery Partner
* Protected routes on frontend & backend

---

## 🔄 Order Lifecycle

User places order → Payment processed →
Admin updates status → Delivery partner delivers →
User receives real-time updates + live tracking

---

## 📁 Project Structure

```
food-delivery/
│
├── backend/
│   ├── routes/
│   ├── middleware/
│   ├── db.js
│   ├── socket.js
│   └── server.js
│
├── frontend/
│   ├── components/
│   ├── pages/
│   └── api.js
```

---

## ⚙️ Setup Instructions

### 1️⃣ Clone Repository

```bash
git clone https://github.com/your-username/food-delivery.git
```

---

### 2️⃣ Backend Setup

```bash
cd backend
npm install
```

Create `.env`:

```
DB_HOST=your_host
DB_USER=your_user
DB_PASSWORD=your_password
DB_NAME=food_delivery
JWT_SECRET=your_secret
```

Run server:

```bash
node server.js
```

---

### 3️⃣ Frontend Setup

```bash
cd frontend
npm install
npm start
```

---

## 🌐 Deployment

* Frontend: Vercel
* Backend: Render
* Database: Railway

---

## 💡 Key Highlights

✔ Full-stack architecture
✔ Real-time updates (WebSockets)
✔ Multi-role system (User, Admin, Delivery Partner)
✔ Cart + Payment system
✔ Live tracking simulation
✔ Scalable database design

---

## 🎯 Future Improvements

* Real payment gateway integration
* Push notifications
* Advanced analytics dashboard
* Mobile responsiveness

---

## 🏆 Resume Impact

This project demonstrates:

* Strong DBMS + SQL skills
* Backend API development
* Authentication & security
* Real-time system design
* Full stack integration

---

## 👩‍💻 Author

**Akanksha Giri**

---

## ⭐ If you like this project

Give it a star ⭐ on GitHub!
