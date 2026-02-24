🛫 Airlines Management System – DBMS Project
Airlines Management System is a web-based application built using HTML, PHP, and MySQL. It simulates airline management operations, including flight management, user registration/login, and admin controls, making it an ideal mini project for DBMS learning and submission.
💻 Technologies Used
Frontend: HTML, CSS
Backend: PHP
Database: MySQL
Server: XAMPP (Apache + MySQL)
🔑 Features
Admin Panel
Secure login (admin/admin)
Add and manage flights
View all users and flight details
User Panel
User registration and login
View available flights
Optional flight booking (advanced version)
Database
Stores users and flights
Easily extendable for booking and ticket management
🛠 Installation / How to Run
Install XAMPP on your computer.
Copy Project Files:
Place all project files in a folder inside htdocs (e.g., AirlinesManagement).
Start Server: Open XAMPP → Start Apache and MySQL.
Setup Database:
Open phpMyAdmin (http://localhost/phpmyadmin)
Create a new database named dbms
Import the dbms.sql file included in the project
Access the Project:
Open browser and go to:
Copy code

http://localhost/AirlinesManagement/homepage.html
🔐 Default Login Credentials
Admin:
Username: admin
Password: admin
User:
Users must register via User Register page
📂 Project Structure
Copy code

AirlinesManagement/
│
├── homepage.html
├── db.php
├── user_register.php
├── user_login.php
├── admin_login.php
├── admin_dashboard.php
├── add_flight.php
├── view_flights.php
├── logout.php
└── dbms.sql
📌 Notes
Before using the system, initialize airline details by inserting Airline ID & Airline Name into the flights table.
You can expand this project to include booking, cancellations, ticket generation, and more.
📈 Optional Enhancements
Flight search with filters
Ticket booking and cancellation system
Passenger profile pages
Admin dashboard with full CRUD operations
Beautiful UI using Bootstrap
🔗 Live Demo (Local)
Access via:
Copy code

http://localhost/AirlinesManagement/homepage.html# Airlines-Management-System
Airlines Management System is a web-based application developed using HTML, PHP, MySQL, and XAMPP. The system simulates airline management operations and ticket booking functionalities. It is designed as a mini DBMS project to demonstrate the use of database operations, user authentication, and CRUD functionality in a real-world scenario.
