# categoria.html – Category View Template

`categoria.html` is the template responsible for displaying each product category within the web application.  
It shows all products belonging to a specific category and allows users to filter and sort them by price.

## 📌 Main Purpose

This template is used to:
- Display products from a selected category
- Filter products by price range
- Sort products by price (ascending or descending)

It provides a consistent layout for all categories across the platform.

## 🧩 Key Features

### 🛍️ Product Browsing
- Dynamic product listing per category
- Price-based filtering
- Price sorting (low to high / high to low)
- Empty-state handling when no products are found

### ❤️ Favorites & 🛒 Cart
- Users can add products to favorites
- Users can add products to the shopping cart
- Visual indicators for favorite and cart items
- Favorites and cart counters displayed in the navbar

### 🔍 Global Navigation
All HTML pages share a common **navbar**, which includes:
- Product search system
- Category navigation
- Access to favorites
- Access to shopping cart
- Login / Register or User Account options

## 👤 User System

The application includes:
- User registration and login system
- Secure authentication using MySQL
- Encrypted passwords
- SQL injection protection
- Persistent user data stored in the database

Each user has access to a **profile section**, with different HTML views where they can:
- Edit personal information
- View current orders
- Check order history

## 🛠️ Admin Panel

The admin panel allows administrators to:
- Edit and delete users
- Add, edit, and delete products
- Add, edit, and delete categories
- View and manage orders

## 💳 Payments

This is a **basic web application**, therefore:
- No payment gateway is implemented
- Orders are stored and managed internally without online payments

## ⚙️ Technologies Used

- HTML5
- CSS3 (custom professional design)
- Flask (Jinja2 templates)
- MySQL database
- Font Awesome
- Bootstrap (layout support)

## ♻️ Reusability

`categoria.html` is reusable for all categories by dynamically loading category data from the database through Flask routes.

## 📁 Project Context

This template is part of a Flask-based e-commerce style web application designed for learning and demonstration purposes, focusing on structure, security, and user interaction rather than payment processing.

---

© 2025 – ChromaWear - pbenavides908
