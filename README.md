
# 🚗 Parking Management System

The **Parking Management System** is a web-based application designed to streamline the process of managing vehicle parking spaces. This system allows users to book, manage, and track parking slots efficiently.

---

## 🚀 Features

- 🅿️ Add/Remove parking slots  
- 🚘 Vehicle entry and exit logging  
- ⏱️ Time-based tracking and billing  
- 👥 Admin and user roles  
- 📊 Dashboard for slot availability and reports

---

## 🛠️ Technologies Used

- Frontend: HTML, CSS, JavaScript  
- Backend: PHP  
- Database: MySQL  
- Optional: Bootstrap for responsive design

---

## 📥 Installation

1. Clone the repository:
```bash
git clone https://github.com/your-username/parking-management.git
```

2. Import the SQL database:
   - Open phpMyAdmin
   - Create a new database (e.g., `parking_db`)
   - Import `parking_db.sql`

3. Set up your server (e.g., XAMPP or WAMP):
   - Place the project in the `htdocs` folder (XAMPP)

4. Configure `db.php` or connection file with your database credentials.

---

## 🧑‍💻 Usage

- Start Apache and MySQL from your XAMPP control panel
- Visit `http://localhost/parking-management/`
- Login using admin/user credentials
- Start managing parking slots!

---

## 📁 Folder Structure

```
parking-management/
│
├── admin/
│   ├── dashboard.php
│   └── manage_slots.php
│
├── user/
│   ├── book_slot.php
│   └── my_bookings.php
│
├── includes/
│   └── db.php
│
├── css/
│   └── style.css
│
├── js/
│   └── script.js
│
├── index.php
├── README.md
└── parking_db.sql
```

---

## 📝 Example Use Case

1. A user logs in and books a slot.
2. Admin approves or tracks all vehicle entries.
3. System records entry and exit times.
4. Billing is generated based on duration.

---

## ✅ Future Enhancements

- QR code-based slot scanning  
- Email/SMS notifications  
- Payment gateway integration

---

## 👩‍💻 Author

Sneha Kohli  
[GitHub](https://github.com/snehakohli)
