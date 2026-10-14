# 🎓 Smart Campus Operations Hub

Smart Campus Operations Hub is a full-stack web application designed to improve the management of university campus facilities and operational activities.

The platform allows students and staff to browse campus resources, make facility bookings, report maintenance issues, receive notifications, and securely access the system using Google authentication.

This project was developed for the **Programming Applications and Frameworks (IT3030)** module at the **Sri Lanka Institute of Information Technology (SLIIT)**.

---

## 🚀 Features

### 🏫 Facility & Resource Management
- View available campus resources
- Add, update, and delete resources
- Search and filter resources
- Manage lecture halls, laboratories, meeting rooms, libraries, offices, and equipment
- Track resource availability and status

### 📅 Booking Management
- Create facility booking requests
- View personal booking history
- Prevent overlapping bookings using conflict detection
- Approve or reject bookings
- Cancel bookings
- Update booking details
- Track booking status

Booking workflow:

Pending → Approved / Rejected → Cancelled

### 🛠️ Maintenance & Incident Ticketing
- Create maintenance and incident reports
- Upload attachments to tickets
- Track ticket progress
- Assign technicians
- Update ticket status
- Add resolution notes
- Add comments to tickets

Ticket workflow:

Open → In Progress → Resolved → Closed

### 🔔 Notification System
Users receive notifications for:
- Booking approvals
- Booking rejections
- Ticket status updates
- New ticket comments

### 🔐 Authentication & Authorization
- Google OAuth 2.0 authentication
- JWT-based API authentication
- Role-Based Access Control
- User and Administrator roles
- Protected API endpoints

---

## 🛠️ Tech Stack

### Frontend
- React.js
- JavaScript
- HTML5
- CSS3
- Axios / Fetch API

### Backend
- Java
- Spring Boot
- Spring Security
- Spring Data
- RESTful APIs
- OAuth 2.0
- JWT

### Database
- MongoDB

### Development Tools
- Git
- GitHub
- GitHub Actions
- Postman
- VS Code
- Draw.io

---

## 🏗️ System Architecture

The application follows a three-tier architecture:

```text
React Frontend
      │
      │ HTTP / JSON
      ▼
Spring Boot REST API
      │
      ▼
MongoDB Database
