# 🛍️ Ziadera Store — Full-Stack E-Commerce Platform

> A modern full-stack e-commerce platform built with **Django** and **Angular 20**, featuring product discovery, authentication, shopping cart, orders, reviews, and online payments.

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

## 📂 Repositories

### 🎨 Frontend

[Angular-Store](https://github.com/ziadshalaby00/Angular-Store)

Angular storefront with product browsing, authentication, cart, user dashboard, and responsive UI.

### ⚙️ Backend

[Django-Store](https://github.com/ziadshalaby00/Django-Store)

Django REST API providing authentication, products, cart, orders, reviews, addresses, and Paymob payments.

## 🚀 Getting Started

See the individual repositories for installation and configuration instructions.

* **Frontend:** [Angular-Store](https://github.com/ziadshalaby00/Angular-Store)
* **Backend:** [Django-Store](https://github.com/ziadshalaby00/Django-Store)

## 📜 License

**MIT License**

---

### 👨‍💻 Developed by [Ziad Shalaby](https://github.com/ziadshalaby00)
