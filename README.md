
# 🛒 E-Commerce Full Stack Project

A modern full-stack e-commerce web application built using **React** for the frontend and **Spring Boot** for the backend. This project features secure authentication, product browsing, cart functionality, and payment gateway integration using Razorpay.

---

## 📌 Features

- 🔐 User Authentication (JWT based)
- 🛍️ Product Listing and Categories
- 🛒 Cart and Checkout Functionality
- 📦 Order Placement and Management
- 💳 Razorpay Payment Integration (Configurable)
- 📂 Admin Features (Add/Edit/Delete Products)
- 📄 API tested via Postman Collection

---

## 🛠️ Tech Stack

| Frontend | Backend     | Database | Security | Tools        |
|----------|-------------|----------|----------|--------------|
| React    | Spring Boot | MySQL    | JWT      | Postman, Maven |

---

## 🚀 Getting Started

### 1. Backend (Spring Boot)

```bash
cd ecommerce-server
mvn spring-boot:run
```

📁 Config:  
Edit `src/main/resources/application.properties` to set your DB and Razorpay keys.

---

### 2. Frontend (React)

```bash
cd react
npm install
npm start
```

---

### 3. MySQL Setup

- Create a DB called `ecommerce`
- Use a compatible schema if available
- Ensure credentials match in `application.properties`

---

## 📂 Folder Structure

- `ecommerce-server/` – Spring Boot backend
- `react/` – React frontend
- `Ecommerce Api.postman_collection.json` – API testing collection

---

## 📷 Screenshots

> Add screenshots of:
> - Home Page
> - Product Page
> - Cart
> - Admin Panel (if implemented)

---

## 📄 API Testing

Use `Ecommerce Api.postman_collection.json` to explore and test all API endpoints.

---

## 👤 Author

**Tauhid Ali**  
BCA Graduate | Full Stack Developer  
[LinkedIn](https://linkedin.com/in/your-profile)  
[GitHub](https://github.com/your-username)

---

## 📃 License

This project is for educational purposes and open for improvements.
