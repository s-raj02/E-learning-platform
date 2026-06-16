# Learnify
[![Framework](https://img.shields.io/badge/Architecture-Full%20Stack-blue.svg)](#-tech-stack)
[![Contributions Welcome](https://img.shields.io/badge/Contributions-Welcome-brightgreen.svg)](CONTRIBUTING.md)

Learnify is a comprehensive, scalable full-stack e-learning platform designed to provide a seamless learning experience for both students and educators. It bridges the gap between instructors and learners by enabling efficient course management, secure user registration, progress tracking, and interactive dashboards for different user roles. With its intuitive and feature-rich interface, Learnify supports learning, collaboration, and resource sharing in a structured and engaging way.


---

## 🚀 Key Features

- **Multi-Role Authentication:** Dedicated dashboards and logic paths for **Students**, **Instructors**, and **Administrators**.
- **Course Management System:** Instructors can easily create, update, and manage course materials, dynamic modules, and media assets.
- **Student Enrollment Pipeline:** Smooth browse-to-enroll experience with progress tracking metrics to see how much of a course is completed.
- **Secure Access Control:** Secured user sessions with stateful or token-based authentication protocols protecting private platform routes.
- **Admin Command Center:** High-level dashboard allowing administrators to monitor platform health, approve creators, and manage global records.

---

## 🛠️ Tech Stack

- **Frontend:** Modern responsive UI built with HTML5, CSS3, JavaScript / React (dynamic layouts).
- **Backend:** Scalable server logic implemented with Node.js/Express (or Python/Java backend frameworks).
- **Database:** Optimized schema architecture using relational (MySQL/PostgreSQL) or non-relational (MongoDB) solutions for persistent storage.

---

## 📂 Project Structure

```text
E-learning-platform/
├── backend/               # Server-side logic, controllers, and routing
│   ├── config/            # Database and environment configurations
│   ├── models/            # Database schemas / Entity blueprints
│   ├── routes/            # API endpoints mapping
│   └── server.js          # App entry point
├── frontend/              # Client-side user interface
│   ├── public/            # Static assets and index files
│   ├── src/               # UI components, pages, and styles
│   └── package.json       # Frontend dependencies
├── database/              # DB migration files or .sql initialization dumps
├── .env.example           # Shared placeholder environment variables
└── README.md              # Project documentation
```
##💻 Installation & Local Setup
Follow these directions to spin up the platform environment on your local machine:

1. Clone the Repository
Bash
git clone [https://github.com/s-raj02/E-learning-platform.git](https://github.com/s-raj02/E-learning-platform.git)
cd E-learning-platform
2. Configure Database & Environment
Open your database GUI/CLI tool.

Create a new database workspace (e.g., elearning_db).

Import any initialization files located in the database/ folder.

Create a .env file in your server directory matching the variables highlighted in .env.example:

Code snippet
```text
PORT=5000
DB_HOST=localhost
DB_USER=root
DB_PASS=your_password
JWT_SECRET=your_secret_token
```
3. Initialize Backend Services
Bash
cd backend
npm install   # or alternative package manager setup commands
npm start
4. Initialize Frontend Client
```text
Open a secondary terminal instance from the root project folder:
Bash
cd frontend
npm install
npm start
The client dashboard should automatically mount and serve via your browser at http://localhost:3000.
```

## 📊 Core Application Workflow
Sign Up / Login: A user lands on the portal and registers dynamically as a Student or an Instructor.

Explore Catalog: Students use searching and filtering models to discover relevant video series or tutorial materials.

Course Publishing: Logged-in Instructors use a specialized content form to structure modules and update lecture resources.

Interactive Dashboard: Tracks completed video modules, showing individual metrics per user account.

## 📧 Contact
Project Link: https://github.com/s-raj02/E-learning-platform
