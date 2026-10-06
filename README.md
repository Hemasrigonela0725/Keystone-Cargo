# 🚚 Keystone Cargo

### Courier Tracking and Management System

Keystone Cargo is a web-based courier tracking and management system developed using **PHP and MySQL**. The system provides an organized platform for administrators to manage customers, parcels, delivery updates, tracking history, and reports, while customers can easily track their shipments using a tracking number.

---

## ✨ Features

### 👤 Customer Management
- Add new customers
- View customer details
- Edit customer information
- Delete customer records
- Manage customer contact and address information

### 📦 Parcel Management
- Create and manage parcel bookings
- Store sender and receiver information
- Manage parcel types and delivery details
- Generate and manage tracking numbers
- View complete parcel information
- Edit and delete parcel records

### 📍 Parcel Tracking
Customers can track their parcels using a unique tracking number.

The tracking system provides a clear delivery journey through different stages:

- 📝 Booked
- 📦 Packed
- 🚚 In Transit
- 🛵 Out for Delivery
- ✅ Delivered

### 🕒 Tracking History
- Maintain parcel delivery history
- Display chronological tracking updates
- Show date and time of updates
- Display location and delivery status
- View the complete shipment journey

### 📊 Admin Dashboard
The administrator can manage the complete courier operation through a centralized dashboard.

Features include:

- Customer management
- Parcel management
- Tracking management
- Delivery updates
- Reports
- Tracking history
- System settings

### 📈 Reports
The system provides an administrative reports section for viewing courier and shipment-related information.

### 🔐 Admin Authentication
- Secure admin login interface
- Admin logout functionality
- Protected administrative pages

### 🎨 Responsive User Interface
- Professional courier-themed interface
- Responsive design
- Animated UI elements
- Custom navigation
- Tracking timeline interface
- Customer-friendly tracking page

---

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| **PHP** | Backend development |
| **MySQL** | Database management |
| **HTML5** | Page structure |
| **CSS3** | Styling and responsive design |
| **JavaScript** | Client-side functionality |
| **XAMPP** | Local development server |
| **Git & GitHub** | Version control |

---

## 🏗️ Project Structure

```text
Keystone-Cargo/
│
├── admin/
│   ├── add_customer.php
│   ├── add_parcel.php
│   ├── dashboard.php
│   ├── edit_customer.php
│   ├── edit_parcel.php
│   ├── update_parcel.php
│   ├── update_tracking.php
│   ├── tracking_history.php
│   ├── reports.php
│   ├── settings.php
│   ├── view_customer.php
│   ├── view_parcel.php
│   ├── view_tracking.php
│   ├── login.php
│   └── logout.php
│
├── assets/
│   ├── css/
│   │   ├── style.css
│   │   ├── admin.css
│   │   ├── tracking.css
│   │   ├── animation.css
│   │   ├── responsive.css
│   │   └── home.css
│   │
│   ├── images/
│   │   ├── background.jpg
│   │   └── logo.jpg
│   │
│   └── js/
│       └── main.js
│
├── includes/
│   ├── db.php
│   ├── header.php
│   ├── navbar.php
│   └── footer.php
│
├── uploads/
│   ├── customers/
│   ├── parcels/
│   └── signatures/
│
├── database/
│   └── keystonecargo.sql
│
├── index.php
├── about.php
├── services.php
├── contact.php
├── track.php
└── test_connection.php
