# Store — Full-Stack E-Commerce Platform

<p align="center">
  🎨 <b>Frontend</b> — <a href="https://github.com/ziadshalaby00/Angular-Store">Angular-Store</a>
  <br>
  ⚙️ <b>Backend</b> — <a href="https://github.com/ziadshalaby00/Django-Store">Django-Store</a>
</p>

> A modern full-stack e-commerce platform built with **Django** and **Angular 20**, featuring product discovery, authentication, shopping cart, orders, reviews, and online payments.

<p align="center">
  <img src="./imgs/image 1.png" width="32%">
  <img src="./imgs/image 2.png" width="32%">
  <img src="./imgs/image 3.png" width="32%">
</p>

## ✨ Features

* 🛍️ Product catalog with search, filtering, sorting, and pagination
* 🏷️ Categories, brands, stock status, and price filtering
* 🛒 Shopping cart with stock validation
* 📦 Order management and automatic stock restoration
* 💳 Paymob online payments with webhook handling
* ⭐ Product reviews and ratings
* 🔐 JWT authentication with HTTP-only cookies
* 🔑 Google OAuth 2.0
* 📧 Password reset via email
* 👤 User profiles and multiple addresses
* 🌙 Dark mode
* 📱 Responsive UI

## 🛠️ Tech Stack

### Frontend

**Angular 20 · TypeScript · Tailwind CSS v4 · Signals · HttpClient · ngx-zs-component**

### Backend

**Django 5.2 · Django REST Framework · PostgreSQL · Redis · Celery · SimpleJWT · Paymob**

## 🏗️ Architecture

```text
┌──────────────────┐
│    Angular 20    │
│     Frontend     │
└────────┬─────────┘
         │ REST API
         ▼
┌──────────────────┐
│    Django 5.2    │
│     Backend      │
└───────┬──────────┘
        │
   ┌────┴─────┐
   ▼          ▼
PostgreSQL   Redis
                │
                ▼
              Celery
```

---

### 👨‍💻 Developed by [Ziad Shalaby](https://github.com/ziadshalaby00)
