# QR-AttendanceApp
Link to QR-Attendance Video : https://www.dropbox.com/sh/f1ct9dhl43fm5pj/AABhJBu0RYPd91yfKtpZHdm9a?dl=0
# Full Stack Attendance Management System

This project is a **Full Stack Attendance Management System** designed to manage student attendance, grades, schedules, and administrative tasks. The system supports **QR code generation and scanning** for attendance tracking and provides an **admin interface** for managing users, students, professors, schedules, and grades.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [Database Schema](#database-schema)
- [Contributing](#contributing)
- [License](#license)

## Overview

This application is designed to streamline the attendance process in educational institutions. It helps professors track student attendance using QR codes, allows students to view their schedules and grades, and gives administrators control over managing schedules, users, and attendance records.

### Key Features:
- **QR Code Generation & Scanning**: Professors can generate QR codes for classes. Students can scan these codes using their mobile devices to mark attendance.
- **Attendance Tracking**: Automatically records and tracks student attendance in real-time.
- **Grades Management**: Allows professors to input grades for assignments and exams, which can be accessed by students.
- **Schedules**: Professors and students can view their personalized schedules.
- **Admin Dashboard**: Provides administrative users with the ability to manage users, courses, and attendance records.
  
## Tech Stack

This project is built using the following technologies:
- **Frontend**: Angular
  - Responsive web interface
  - QR code generation & scanning functionality
- **Backend**: ASP.Net Core WebAPI
  - RESTful API endpoints for managing user data, attendance, grades, and schedules
- **Database**: MySQL
  - Structured relational database for storing user and attendance data
- **Authentication**: JWT (JSON Web Tokens)
  - Secure authentication for users (students, professors, admins)

## Installation

### Prerequisites
Before running this application, you need to have the following installed:
- **Node.js** (for Angular frontend)
- **.NET Core SDK** (for ASP.NET Core Web API)
- **MySQL** (for database)

### Steps to Run Locally

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/attendance-app.git
