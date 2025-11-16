
Savion Sports Club Management System

A web-based Sports Club Management System developed using PHP and MySQL to streamline the management of students, coaches, equipment, schedules, and administrative operations. The system includes secure, role-based dashboards for Admin, Coaches, and Students, ensuring smooth coordination and efficient workflow within the sports club.

🚀 Overview

This system digitizes key activities of a sports club such as tracking attendance, managing equipment, handling user registrations, scheduling events, and generating PDF reports. It supports seamless communication among users and provides a structured, secure environment for data management.

✨ Key Features
🔹 Admin Panel

Manage Students, Coaches, & Staff

Approve/Reject user requests

Equipment management (add/update/delete)

Generate PDF reports using TCPDF

Send notifications to users

View system statistics

🔹 Coach Panel

View assigned students

Manage attendance

Access daily/weekly schedules

Raise requests to admin

🔹 Student Panel

View personal profile

Check assigned coach & schedules

Submit requests or queries

Receive admin/coach notifications

🔹 General Features

Secure login for all roles

Clean and structured MySQL database

PDF generation for downloadable reports

Fully functional CRUD operations

🛠️ Tech Stack

Frontend: HTML, CSS, JavaScript

Backend: PHP

Database: MySQL

Library: TCPDF (PDF Report Generation)

Server: XAMPP / WAMP / LAMP

📂 Project Structure
Sports/
│── index.php
│── login.php
│── register.php
│── register_coach.php
│── register_student.php
│── database.sql
│
├── admin/
│   ├── dashboard.php
│   ├── add_user.php
│   ├── edit_user.php
│   ├── equipment.php
│   ├── notifications.php
│   ├── print_request.php
│
├── coach/
│   ├── dashboard.php
│   ├── attendance.php
│   ├── students.php
│   ├── schedule.php
│
├── student/
│   ├── dashboard.php
│   ├── profile.php
│   ├── schedule.php
│   ├── request.php
│
└── vendor/tcpdf/
    ├── fonts/
    └── tcpdf.php

▶️ How to Run the Project

Download or Clone the Repository

git clone <repository-url>


Move the project folder to server directory:

XAMPP → htdocs/

WAMP → www/

Import the Database

Open phpMyAdmin

Create a database (example: sports_db)

Import the database.sql file

Configure Database Connection

Update DB credentials in relevant PHP config files (if provided)

Start Server

Start Apache & MySQL

Open in Browser

http://localhost/Sports/

🔮 Future Enhancements

Admin analytics dashboard

Online fees/payment module

Email/SMS notifications

Attendance analytics & performance charts

Mobile-friendly responsive UI

📘 Conclusion

The Savion Sports Club Management System offers a complete digital solution for managing sports club activities efficiently. It simplifies coordination between admin, coaches, and students while maintaining secure user access and structured data handling.
