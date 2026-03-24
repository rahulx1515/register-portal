# 🚀 Smart Complaint Register Portal

![React](https://img.shields.io/badge/Frontend-React-blue?style=for-the-badge&logo=react)
![Appwrite](https://img.shields.io/badge/Backend-Appwrite-pink?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Active-success?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

> A modern **Complaint Management System** designed to streamline grievance handling with real-time tracking, role-based dashboards, and automated notifications.

---

## 📌 Overview

The **Smart Complaint Register Portal** is a web-based platform that replaces traditional manual complaint systems with a **fast, transparent, and efficient digital solution**.

It allows:
- Students to submit and track complaints
- Admins to manage and resolve issues
- Institutions to improve transparency and response time

---

## 🎯 Objectives

- Provide an **online complaint submission platform**
- Enable **real-time status tracking** (Pending → In-Progress → Resolved)
- Support **department-wise complaint handling**
- Improve **resolution time**
- Offer **analytics & insights for admins**

---

## 👥 User Roles

### 👨‍🎓 Student
- Submit complaints (Hostel / Food / Other)
- Track complaint status
- View complaint history

### 🏢 Department Admin (Hostel / Food / Other)
- View department-specific complaints
- Update complaint status
- Search, filter & export data
- View analytics dashboard

### 🧑‍💼 Super Admin
- Access all complaints
- Monitor system performance
- Manage overall analytics
- Export complete data

---

## ✨ Features

- 📝 Complaint Submission System  
- 📊 Dashboard Analytics (Charts & Stats)  
- 🔍 Search & Filter Complaints  
- 🔐 Secure Authentication (Role-based)  
- ⚡ Real-time Updates  
- 📧 Email Notifications (Automation)  
- 📁 Data Export (CSV/Excel)  
- 📱 Fully Responsive UI  

---

## 🛠️ Tech Stack

### Frontend
- React.js  
- Tailwind CSS  
- JavaScript (ES6+)  
- Recharts (for analytics)

### Backend
- Appwrite (Authentication + APIs)
- Role-Based Access Control

### Database
- Appwrite Database

### Automation
- n8n (Email notifications)

---

## 📊 System Modules

- 🔐 Authentication Module  
- 👨‍🎓 Student Module  
- 📋 Complaint Management Module  
- 📊 Admin Dashboard Module  
- 🧑‍💼 Super Admin Module  
- 📈 Analytics & Reporting Module  
- 📧 Email Notification Module  

---

## 🔄 Complaint Workflow

1. Student submits complaint  
2. Complaint stored with **Pending status**  
3. Assigned to respective department  
4. Admin updates status → In-Progress / Resolved  
5. Student receives real-time updates + email  

---
## 📂 Folder Structure

src/
│
├── assets/
│   └── react.svg
│
├── components/
│   ├── common/
│   │   ├── Navbar.jsx
│   │   ├── Card.jsx
│   │   └── Loader.jsx
│   │
│   ├── admin/
│   ├── home/
│   └── students/
│
├── pages/
│   ├── HomePage.jsx
│   ├── LoginPage.jsx
│   ├── Dashboard.jsx
│   └── SubmitComplaint.jsx
│
├── services/
│   ├── authService.js
│   └── complaintService.js
│
├── utils/
│   └── helpers.js
│
├── App.jsx
├── main.jsx
├── App.css
└── index.css
---

## ⚙️ Installation & Setup

```bash
# Clone repository
git clone https://github.com/rahulx1515/complaint-portal.git

# Navigate to project
cd cp/cp

# Install dependencies
npm install

# Run project
npm run dev