# buinhanthe.github.io
# 🛒 Shop Online - E-commerce Website (Laravel)

## 📌 Introduction

This project is a full-featured **E-commerce web application** built using Laravel.
It simulates a real-world online shopping system with user and admin functionalities.

The main goal of this project is to practice backend development, database design, and system architecture using Laravel.

---

## 🚀 Technologies Used

* **Backend:** PHP (Laravel Framework)
* **Frontend:** Blade Template, Bootstrap 5
* **Database:** MySQL
* **Other Tools:** Git, GitHub, XAMPP/Laragon

---

## ⚙️ Features

### 👤 User Features

* Register / Login / Logout
* Browse products
* Add to cart
* Place orders
* View order history

### 🛠️ Admin Features

* Manage products (CRUD)
* Manage users
* Manage orders
* Role-based access control (Admin/User)

---

## 🧠 System Design

### Database Design

* Designed relational database with optimized structure
* Used indexing to improve query performance

### Architecture

* Applied **MVC pattern** in Laravel
* Separated logic clearly:

  * Model → Database
  * Controller → Business logic
  * View → UI

---

## 📂 Project Structure

```bash
app/
 ├── Models/
 ├── Http/
 │    ├── Controllers/
resources/
 ├── views/
routes/
 ├── web.php
```

---

## ▶️ Installation Guide

### 1. Clone project

```bash
git clone https://github.com/yourusername/shop-online.git
cd shop-online
```

### 2. Install dependencies

```bash
composer install
npm install
```

### 3. Setup environment

```bash
cp .env.example .env
php artisan key:generate
```

### 4. Configure database

* Update `.env`:

```
DB_DATABASE=shop
DB_USERNAME=root
DB_PASSWORD=
```

### 5. Run migration

```bash
php artisan migrate
```

### 6. Start server

```bash
php artisan serve
```

👉 Access: http://127.0.0.1:8000

---

## 📸 Screenshots

*(Add your images here)*

* Homepage
* Product page
* Cart page
* Admin dashboard

---

## 📈 Results Achieved

* Built a complete CRUD system
* Implemented authentication & authorization
* Designed optimized database
* Applied clean code structure (MVC)
* Improved backend logic and debugging skills

---

## 🔮 Future Improvements

* Integrate online payment (VNPay, PayPal)
* Add RESTful API for mobile app
* Implement Redis caching
* Apply Docker for deployment

---

## 📬 Contact

* GitHub: https://github.com/yourusername
* LinkedIn: https://linkedin.com/in/yourname
* Email: [your@email.com](mailto:your@email.com)
