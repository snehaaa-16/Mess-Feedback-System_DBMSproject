# Mess Feedback System – DBMS Project

## Overview

The **Mess Feedback System** is a PHP–MySQL based web application that allows students to submit feedback about their hostel/college mess. Administrators can view, manage, and act upon the submitted feedback.

This project was developed as part of a **DBMS mini-project**, demonstrating SQL operations, authentication, CRUD features, and database connectivity through PHP.

## Features

* User login & authentication
* Submit feedback
* View feedback
* Admin controls (approve/view/manage feedback)
* Update/Delete operations
* MySQL database schema included

## Tech Stack

| Component | Technology               |
| --------- | ------------------------ |
| Frontend  | HTML, CSS, JavaScript    |
| Backend   | PHP                      |
| Database  | MySQL                    |
| Server    | Apache (XAMPP/WAMP/LAMP) |

## Project Structure

```
Mess-Feedback-System/
│── login.php
│── feedback.php
│── feedback-server.php
│── update.php
│── forgot.php
│── logout.php
│── main.js
│── header.php
│── home.php
│── user.php
│── Database-project.sql
│── README.md
```

## Database Setup

1. Open phpMyAdmin
2. Create a database (e.g., `mess_feedback`)
3. Import the file:

   ```
   Database-project.sql
   ```
4. Update DB credentials in PHP files if needed.

## How to Run

1. Install XAMPP/WAMP/LAMP
2. Place the project folder in:

   ```
   htdocs/ (for XAMPP)
   www/ (for WAMP)
   ```
3. Start Apache & MySQL
4. Open in browser:

   ```
   http://localhost/Mess-Feedback-System/
   ```

---
