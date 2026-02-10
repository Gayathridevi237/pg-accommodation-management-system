PG Life – Accommodation Finder Web Application
Overview

PG Life is a full-stack web application developed to assist users in discovering and managing Paying Guest (PG) accommodations across multiple cities. The application provides secure user authentication, city-based property listings, detailed property views, and a personalized dashboard for managing interested properties. The system simulates a real-world accommodation discovery platform with a structured frontend–backend architecture.

Objectives

To provide a centralized platform for PG accommodation discovery

To implement secure user authentication and session handling

To enable users to shortlist and manage preferred properties

To deliver a responsive and intuitive user interface

Key Features

Secure user signup and login using PHP sessions

City-wise PG accommodation listings

Detailed property information including amenities and pricing

Interested (wishlist) functionality with real-time updates

Personalized user dashboard

Responsive UI using Bootstrap

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

Frontend handles user interaction and UI rendering

Backend processes business logic and database communication

AJAX is used for asynchronous operations such as interest toggling

MySQL database stores user, property, and interest data

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
│   │   └── application assets and icons
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

Move the project folder into the web server directory:

htdocs/


Start Apache and MySQL services.

Open phpMyAdmin and create a database.

Import the provided SQL file (if available).

Update database connection credentials in PHP files if required.

Access the application via browser:

http://localhost/pg-life-accommodation-finder/PGLIFE/

Backend API Endpoints
Endpoint	Description
login_submit.php	Handles user authentication
signup_submit.php	Handles new user registration
toggle_interested.php	Adds or removes interested properties
handle_interested_dashboard.php	Retrieves dashboard data
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

Limited search and filtering capabilities

Basic authentication security

Future Enhancements

Advanced search and filtering options

Google Maps integration

Ratings and reviews system

Admin dashboard

Enhanced password encryption and security

Author

Gayathri Devi
Integrated M.Tech – Software Engineering
