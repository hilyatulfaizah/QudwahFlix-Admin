# 📘 QudwahFlix Admin Dashboard — Project Documentation

## 📌 Overview
QudwahFlix Admin Dashboard is a web-based management system built to control and monitor all operations of the QudwahFlix platform, including users, courses, products, orders, and payments.

The system provides administrators with a centralized interface to manage content and track platform activities in real-time.

---

## 🚀 Key Features

### 🔐 Admin Authentication
- Secure admin login system  
- Role-based access control  
- Protected admin routes  

---

### 👥 User Management
- View all registered users  
- Edit user information  
- Delete or manage user accounts  
- Monitor user activity  

---

### 🎥 Course Management
- Add new courses  
- Update course details  
- Delete or manage content  
- Control course availability  

---

### 🛍️ Product Management
- Add and manage products  
- Update pricing and details  
- Handle product listings  

---

### 📦 Order Management
- View customer orders  
- Track order status  
- Update order progress  
- Manage delivery or fulfillment  

---

### 💳 Payment Monitoring
- Track subscription payments  
- Monitor installment payments  
- Verify transaction status  
- Real-time payment updates  

---

### 📊 Dashboard Analytics
- Overview of users, sales, and orders  
- Quick insights into platform performance  
- Real-time data visualization  

---

## 🏗 System Architecture

### Frontend
- Flutter Web / React (based on implementation)  
- Responsive dashboard UI  
- Component-based structure  

### Backend (Firebase)
- Firebase Authentication (admin access)  
- Cloud Firestore (data management)  

### External Integrations
- Payment gateway integration (e.g., SenangPay)  

---

## 🔄 Key Workflows

### Order & Payment Flow
1. User makes a purchase (mobile app)  
2. Payment processed via payment gateway  
3. Transaction stored in Firestore  
4. Admin dashboard retrieves data in real-time  
5. Admin monitors and updates order/payment status  

---

### Content Management Flow
1. Admin logs into dashboard  
2. Admin performs CRUD operations (courses/products)  
3. Data updated in Firestore  
4. Changes reflected instantly in mobile app  

---

## 📂 Project Structure (Simplified)

```
src/
├── pages/
├── components/
├── services/
├── models/
└── main.dart / App.js
```

---

## 🧠 My Contributions
- Developed admin dashboard interface  
- Implemented CRUD operations for multiple modules  
- Integrated Firebase for real-time data updates  
- Designed user-friendly dashboard layout  
- Managed API and database connections  

---

## ⚡ Highlights
- Real-time admin monitoring system  
- Centralized control for entire platform  
- Scalable and modular dashboard design  
- Clean UI for efficient management  

---

## 📌 Notes
This system is used for internal management and is **not publicly deployed**.  
The project showcases dashboard development and system integration skills.

---

## 🧑‍💻 Project Context
- Developed during internship  
- Collaborated with a teammate in a small team environment  
