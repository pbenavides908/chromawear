# ChromaWear – Web Application Overview

ChromaWear is a basic e-commerce style web application built with Flask and MySQL.  
The project focuses on product management, user authentication, and a complete browsing experience without implementing online payments.

## 🛍️ Product & Category System

The application allows users to browse products by category.  
Each category displays its products dynamically and supports:
- Price filtering
- Price sorting (ascending and descending)

The category view is part of a reusable template system used across the site.

## 🔍 Navigation & User Experience

All pages share a global **navbar**, which provides:
- Product search functionality
- Access to all categories
- Favorites overview
- Shopping cart overview
- Login, registration, and user account access

## ❤️ Favorites & 🛒 Cart

Users can:
- Add and remove products from favorites
- Add products to a shopping cart
- View favorites and cart contents at any time

These features work without a payment gateway and are designed for browsing and order management purposes.

## 👤 User Accounts & Security

The application includes a complete user system:
- User registration and login
- Password encryption
- MySQL database persistence
- SQL injection protection

Each user has a personal profile section with different views where they can:
- Edit personal information
- View orders and order history

## 🛠️ Admin Management

An advanced admin panel allows administrators to:
- Edit and delete users
- Add, edit, and manage products
- Create and manage categories
- View and manage orders

## 💳 Payments

This project does **not** include an online payment system.  
Orders are stored for tracking and demonstration purposes only.

## ⚙️ Technologies Used

- Flask (Python)
- HTML5 & CSS3 (custom professional design)
- MySQL
- Bootstrap
- Font Awesome

## 🎯 Project Purpose

ChromaWear is intended as a learning and demonstration project, showcasing full CRUD functionality, secure authentication, and structured web application design.

---

© 2025 – ChromaWear - pbenavides908

