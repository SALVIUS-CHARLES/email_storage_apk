# Email Collector Project

This project is a simple web application that collects email addresses from users and stores them in a MySQL database. It uses Docker to containerize the application, making it easy to set up and run.

---

## Features
- Collects email addresses through a web form.
- Validates email addresses before saving them to the database.
- Prevents duplicate email entries using `INSERT IGNORE`.
- Includes a `phpMyAdmin` interface for managing the database.

---

## Technologies Used
- **PHP**: Backend logic for handling form submissions and database interactions.
- **MySQL**: Database for storing email addresses.
- **phpMyAdmin**: Web-based interface for managing the database.
- **Docker**: Containerization for easy setup and deployment.

---

## Project Structure

# how tu run the project
Try submitting emails through the form at http://localhost

View the collected emails at http://localhost/view_emails.php

Explore the database structure in phpMyAdmin at http://localhost:8080