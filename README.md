PG Life – Accommodation Finder Web Application
Overview

PG Life is a full-stack web application designed to help users discover and manage Paying Guest (PG) accommodations across multiple cities. The application provides secure user authentication, city-based property listings, detailed property information, and a personalized dashboard for managing shortlisted properties. The system reflects a real-world accommodation discovery platform with a clear separation between frontend and backend components.

Objectives

Provide a centralized platform for PG accommodation discovery

Implement secure user authentication and session management

Enable users to shortlist and manage preferred properties

Deliver a responsive and user-friendly interface

Key Features

Secure user signup and login using PHP sessions

City-wise PG accommodation listings

Detailed property pages with amenities and pricing

Interested (wishlist) functionality with real-time updates

Personalized user dashboard

Responsive UI built with Bootstrap

Technology Stack
Frontend

HTML5

CSS3

Bootstrap

JavaScript (AJAX)

Backend

PHP

MySQL

Tools and Environment

XAMPP / WAMP / LAMP

phpMyAdmin

System Architecture

The application follows a client–server architecture:

Frontend

Handles user interaction and UI rendering

Built using HTML, CSS, Bootstrap, and JavaScript

Backend

Processes business logic

Manages authentication and database communication using PHP

Asynchronous Communication

AJAX is used for operations such as interest toggling without page reloads

Database

MySQL stores user, property, and interest-related data

Project Structure
pg-life-accommodation-finder/
│
├── PGLIFE/
│   ├── api/
│   │   ├── login_submit.php
│   │   ├── signup_submit.php
│   │   ├── toggle_interested.php
│   │   └── handle_interested_dashboard.php
│   │
│   ├── css/
│   │   ├── bootstrap.min.css
│   │   ├── common.css
│   │   ├── index.css
│   │   ├── property_list.css
│   │   ├── property_detail.css
│   │   └── dashboard.css
│   │
│   ├── img/
│   │   └── Application assets and icons
│   │
│   ├── index.php
│   ├── property_list.php
│   ├── property_detail.php
│   ├── dashboard.php
│   └── favicon.ico
│
└── README.md

Installation and Setup
Prerequisites

PHP 7.x or later

MySQL

XAMPP / WAMP / LAMP

Web browser

Steps to Run the Application

Clone or extract the repository.

Move the project folder to the web server root directory:

htdocs/


Start Apache and MySQL services.

Open phpMyAdmin and create a new database.

Import the provided SQL file (if available).

Update database credentials in PHP configuration files if required.

Access the application in a browser:

http://localhost/pg-life-accommodation-finder/PGLIFE/

Backend API Endpoints
Endpoint	Description
login_submit.php	Handles user authentication
signup_submit.php	Handles user registration
toggle_interested.php	Adds or removes interested properties
handle_interested_dashboard.php	Retrieves user dashboard data
Functional Modules

Authentication Module

Property Listing Module

Property Detail Module

Interested Properties Module

User Dashboard Module

Security Measures

Session-based authentication

Server-side input validation

Restricted access to user-specific data

Limitations

No admin panel for property management

Limited search and filtering options

Basic authentication security

Future Enhancements

Advanced property search and filtering

Map-based property visualization

Ratings and reviews system

Admin dashboard

Enhanced password encryption and security

Author

Gayathri Devi
Integrated M.Tech – Software Engineering
Full-Stack Web Developer
