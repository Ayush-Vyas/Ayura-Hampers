# 🌿 Ayura Hampers

A full-featured PHP-based e-commerce web application for curated gift hampers, featuring user authentication, order management, admin dashboard, and promotional offers.

---

## 🚀 Features

### 👤 User Side

* User Registration & Login
* Email Verification (OTP-based)
* Browse Hampers & Offers
* Add to Cart & Checkout
* Apply Promo Codes
* Order Tracking
* User Profile Management

---

### 🛠️ Admin Panel

* Admin Login System
* Manage Users
* View & Manage Orders
* Manage Promo Codes
* View Feedback & Contact Messages
* Track Income & Analytics

---

### 📧 Email System

* Integrated with **PHPMailer**
* OTP Verification for Login/Register
* Order-related email handling

---

## 🧰 Tech Stack

* **Frontend:** HTML, CSS, JavaScript
* **Backend:** PHP
* **Database:** MySQL
* **Email Service:** PHPMailer
* **Server (Local):** WAMP / XAMPP

---

## 📁 Project Structure

```
Ayura-Hampers/
│
├── admin/                # Admin panel files
├── img/                  # Images
├── uploads/              # User uploaded files
├── PHPMailer-master/     # Email library
│
├── index.php             # Homepage
├── login.php             # User login
├── register.php          # User registration
├── dashboard.php         # User dashboard
├── checkout.php          # Checkout system
├── place_order.php       # Order processing
├── validate_promo.php    # Promo validation
├── db.php                # Database connection
├── config.php            # Config settings
└── ayura_hampers.sql     # Database file
```

---

## ⚙️ Setup Instructions (Run Locally)

1. Install **WAMP/XAMPP**

2. Place project folder inside:

   ```
   /www (WAMP) OR /htdocs (XAMPP)
   ```

3. Start Apache & MySQL

4. Import database:

   * Open phpMyAdmin
   * Create database: `ayura_hampers`
   * Import `ayura_hampers.sql`

5. Configure database:

   * Update `db.php` / `config.php` with your credentials

6. Run project:

   ```
   http://localhost/AHS/
   ```

---

## 🔐 Important Notes

* Sensitive files (`config.php`, `db.php`) are excluded for security
* Add your own database credentials before running
* Configure SMTP settings in PHPMailer for email functionality

---

## 📸 Screenshots

<img width="1919" height="972" alt="image" src="https://github.com/user-attachments/assets/33b68ad4-7972-421e-a347-f25b63508546" />

* Homepage
* User Dashboard
* Admin Panel

---

## 📌 Future Enhancements

* Payment Gateway Integration
* Mobile Responsive UI Improvements
* Product Categories & Filters
* Live Chat Support
* Deployment on Cloud Hosting

---

## 👨‍💻 Author

**Ayush Vyas**

---

## ⭐ Support

If you like this project, consider giving it a ⭐ on GitHub!

---
