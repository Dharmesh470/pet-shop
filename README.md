# 🐾 Pet Shop - E-Commerce Web Application

A full-featured **Pet Shop E-Commerce** web application built with PHP and MySQL. Browse products, manage your cart, place orders, and handle everything through a powerful admin dashboard.

---

## ✨ Features

### 🛍️ Customer Side
- **Product Browsing** — View products by category & subcategory with image galleries
- **Shopping Cart** — Add/remove items, adjust quantities
- **Checkout & Orders** — Place orders and track order status
- **User Accounts** — Register, login, and manage your profile
- **Responsive Design** — Works on desktop and mobile devices

### 🔧 Admin Panel
- **Dashboard** — Overview of shop statistics
- **Product Management** — Add, edit, and delete products with image uploads
- **Category Management** — Organize products into categories & subcategories
- **Inventory Management** — Track stock levels and pricing by size
- **Order Management** — View and process customer orders
- **User Management** — Manage customer and admin accounts
- **System Settings** — Configure shop name, logo, and other settings

---

## 🛠️ Tech Stack

| Layer      | Technology                        |
|------------|-----------------------------------|
| Backend    | PHP (Vanilla)                     |
| Database   | MySQL                             |
| Frontend   | HTML, CSS, JavaScript, Bootstrap  |
| Server     | Apache (XAMPP / WAMP / LAMP)      |

---

## 📁 Project Structure

```
pet_shop/
├── admin/                  # Admin panel
│   ├── inventory/          # Stock management
│   ├── maintenance/        # Category & subcategory management
│   ├── orders/             # Order processing
│   ├── product/            # Product CRUD
│   ├── system_info/        # System settings
│   └── user/               # User management
├── assets/                 # Static assets (CSS, JS, images)
├── build/                  # Build assets
├── classes/                # PHP classes
│   ├── DBConnection.php    # Database connection handler
│   ├── Login.php           # Authentication logic
│   ├── Master.php          # Core business logic
│   ├── SystemSettings.php  # System configuration
│   ├── Users.php           # User management
│   └── Zone.php            # Zone/location utilities
├── database/               # SQL dump for database setup
│   └── pet_shop_db.sql     # Database schema & seed data
├── dist/                   # Distribution assets
├── inc/                    # Shared includes (header, footer, navbar)
├── libs/                   # Third-party libraries
├── plugins/                # jQuery & Bootstrap plugins
├── uploads/                # User-uploaded product images
├── config.php              # App configuration & helpers
├── initialize.php          # Constants & DB credentials
├── index.php               # Main entry point
├── home.php                # Homepage
├── products.php            # Product listing page
├── view_product.php        # Single product view
├── cart.php                # Shopping cart
├── checkout.php            # Checkout page
├── login.php               # Login page
├── registration.php        # Registration page
├── my_account.php          # User account page
└── edit_account.php        # Edit account details
```

---

## 🚀 Installation & Setup

### Prerequisites
- [XAMPP](https://www.apachefriends.org/) (or any Apache + PHP + MySQL stack)
- PHP 7.4+
- MySQL 5.7+

### Steps

1. **Clone the repository**
   ```bash
   git clone https://github.com/Dharmesh470/pet-shop.git
   ```

2. **Move to your web server directory**
   ```bash
   # For XAMPP
   cp -r pet-shop /path/to/xampp/htdocs/pet_shop
   ```

3. **Create the database**
   - Open [phpMyAdmin](http://localhost/phpmyadmin)
   - Create a new database named **`pet_shop_db`**
   - Import the SQL file located at `database/pet_shop_db.sql`

4. **Configure database credentials**  
   Edit `initialize.php` if your MySQL credentials differ from the defaults:
   ```php
   define('DB_SERVER',   "localhost");
   define('DB_USERNAME', "root");
   define('DB_PASSWORD', "");
   define('DB_NAME',     "pet_shop_db");
   ```

5. **Set the base URL**  
   In `initialize.php`, update the base URL to match your setup:
   ```php
   define('base_url', 'http://localhost/pet_shop/');
   ```

6. **Start Apache & MySQL** via XAMPP Control Panel

7. **Open in browser**
   ```
   http://localhost/pet_shop/
   ```

---

## 🔑 Default Admin Credentials

| Field    | Value           |
|----------|-----------------|
| Username | `admin`         |
| Password | `admin123`      |

> ⚠️ **Change the default credentials** after your first login for security.

---

## 📸 Screenshots



---
---

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/new-feature`)
3. Commit your changes (`git commit -m 'Add new feature'`)
4. Push to the branch (`git push origin feature/new-feature`)
5. Open a Pull Request

---
## AUTHOR 
   Dharmesh shinde 
   

> Built with ❤️ for pet lovers everywhere
