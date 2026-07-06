# Clastic – Smart Waste Management System Application

![Laravel](https://img.shields.io/badge/Laravel-12-red?logo=laravel&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-8.2-777BB4?logo=php&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![REST API](https://img.shields.io/badge/REST_API-green)
![MVC](https://img.shields.io/badge/MVC_Architecture-blue)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)

Clastic is a Laravel-based smart waste management platform developed as part of a Software Engineering project. The application aims to help encourage responsible plastic recycling by integrating waste classification, pickup scheduling, drop-off management, reward points, and educational content into a centralized platform.

---

# 📖 Project Overview

This project has the overview to ditinguish palstic recycling based on categories through a digital platform that connects users with recycling services while promoting environmental awareness.

Users can classify plastic waste, schedule pickups or drop-offs, earn reward points, monitor recycling progress, and access educational content through a centralized web application.

From a software engineering perspective, this project demonstrates the complete development lifecycle—from requirement analysis and UML modeling to backend implementation, database design, RESTful API integration, and software documentation.

---

# Key Features

## End Users

- User Registration & Authentication
- Plastic Classification
- Pickup Scheduling
- Drop-off Scheduling
- Reward Point System
- Mission & Achievement Tracking
- Educational Articles
- Recycling History

## Administration

- User Management
- Pickup Management
- Drop-off Management
- Waste Category Management
- Transaction Monitoring
- Dashboard & Reporting

---

# 🏗 System Architecture

The system follows the Laravel MVC architecture.

```
Presentation Layer
        │
Laravel Blade Views
        │
Controllers
        │
Business Logic
        │
REST API
        │
PostgreSQL Database
```

---

# 🛠 Technology Stack

| Category | Technologies |
|-----------|--------------|
| Frontend | Blade, HTML, CSS, JavaScript |
| Backend | Laravel, PHP |
| Database | PostgreSQL |
| Architecture | MVC Architecture |
| API | RESTful API |
| Development | Git, GitHub |
| Deployment | Docker |

---

# 📂 Project Modules

Authentication

- Register
- Login
- Logout

Plastic Management

- Plastic Classification

Pickup

- Schedule Pickup
- Confirm Pickup Location
- Select Plastic Type
- Input Plastic Quantity
- Pickup Summary

Drop-off

- Schedule Drop-off
- Confirm Drop-off Location
- Select Plastic Type
- Input Plastic Quantity
- Drop-off Summary

Reward System

- Mission Progress
- Achievement Streak
- Redeem Points

---

# 📐 Software Engineering Artifacts

This project follows a structured Software Engineering lifecycle.

Artifacts produced throughout development include:

- Software Requirements Specification (SRS)
- Critical Design Review (CDR)
- Use Case Diagrams
- Sequence Diagrams
- Robustness Diagrams
- Storyboards
- Database Design
- MVC Architecture Design

These documents were used to validate business requirements and system behavior before implementation.

---

# 👨‍💻 My Contribution

This project was developed as a team assignment. 
My primary responsibilities included:

- Developing the complete Pickup module, including scheduling, location confirmation, plastic type selection, quantity input, and pickup summary workflows.
- Implementing backend business logic using Laravel, PostgreSQL, and the MVC architecture.
- Designing and integrating relational database operations supporting pickup transactions.
- Contributing to RESTful API integration between frontend and backend components.
- Producing multiple Sequence Diagrams and Robustness Diagrams covering authentication, pickup workflows, and driver operations as part of the system's engineering documentation.
- Designing storyboards and interaction flows for assigned application modules.
- Collaborating throughout system analysis, implementation, testing, and technical documentation with the development team.

---

# 📚 What I Learned

Through this project, I gained practical experience in:

- Laravel MVC Architecture
- PostgreSQL Database Design
- RESTful API Development
- Authentication & Authorization
- Relational Database Modeling
- UML Modeling
- Sequence Diagram Design
- Robustness Diagram Design
- Software Requirements Specification (SRS)
- Critical Design Review (CDR)
- Collaborative Software Development using Git

---

# 📂 Folder Structure

```
app/
bootstrap/
config/
database/
public/
resources/
routes/
storage/
tests/
```

---

# Installation Process

Clone the repository

```bash
git clone https://github.com/vikakiku/ClasticApp.git
```

Install dependencies

```bash
composer install
npm install
```

Copy the environment file

```bash
cp .env.example .env
```

Generate application key

```bash
php artisan key:generate
```

Configure the PostgreSQL database inside `.env`.

Run migrations

```bash
php artisan migrate
```

Start the application

```bash
php artisan serve
```

---

# Future Improvements

Possible enhancements for future development include:

- Push notifications for pickup reminders
- AI-assisted plastic classification
- QR-based recycling verification
- Route optimization for waste collection
- Mobile application support
- Analytics dashboard for recycling statistics

---

# License

This project was developed collaboratively as part of a Software Engineering course.
This repository is published for educational and portfolio purposes.

© 2025 Clastic Team
