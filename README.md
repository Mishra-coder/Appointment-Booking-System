# 🏥 Smart Appointment Booking System

[![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://reactjs.org/)
[![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)](https://nodejs.org/)
[![Express.js](https://img.shields.io/badge/Express.js-404D59?style=for-the-badge)](https://expressjs.com/)
[![Prisma](https://img.shields.io/badge/Prisma-3982CE?style=for-the-badge&logo=Prisma&logoColor=white)](https://prisma.io/)
[![MySQL](https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white)](https://mysql.com/)

> **College Group Project** - A comprehensive web-based healthcare platform for managing medical appointments between patients, doctors, and administrators.

## 📋 Table of Contents
- [🎯 Project Overview](#-project-overview)
- [👥 College Project Information](#-college-project-information)
- [✨ Key Features](#-key-features)
- [🏗️ Project Structure](#️-project-structure)
- [💻 Tech Stack](#-tech-stack)
- [⚙️ Installation & Setup](#️-installation--setup)
- [🚀 How to Run](#-how-to-run)
- [👤 User Roles](#-user-roles)
- [🔗 API Endpoints](#-api-endpoints)
- [📸 Screenshots](#-screenshots)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)

## 🎯 Project Overview

The **Smart Appointment Booking System** is a modern, full-stack web application designed to revolutionize healthcare appointment management. This system provides a seamless experience for patients to book appointments, doctors to manage their schedules, and administrators to oversee the entire platform.

### 🎯 Problem Statement
Traditional appointment booking systems are often inefficient, leading to:
- Long waiting times for patients
- Poor communication between patients and doctors
- Difficulty in managing schedules
- Lack of digital prescription management

### 💡 Our Solution
A comprehensive digital platform that:
- Streamlines the appointment booking process
- Provides role-based access for different user types
- Enables digital prescription management
- Offers real-time appointment tracking
- Ensures secure user authentication

## 👥 College Project Information

### 🎓 Academic Details
- **Course**: B.tech CSE & AI-ML
- **Project Type**: Group Project (Full Stack Development)
- **Duration**: 3 Months
- **Academic Year**: 2025

### 👨‍💻 Team Members
| Name | Role | Responsibilities |
|------|------|-----------------|
| Pratik Kumar Pan | Frontend Developer | React.js, UI/UX Design |
| Adarsh Priydarshi & Ayush Kumar Jha | Backend Developer | Node.js, API Development |
| Devendra Mishra | Database Designer | Prisma, MySQL Schema |
| Ayush Kumar Jha & Adarsh Priydarshi | Project Manager | Documentation, Testing |


### 🎯 Learning Objectives
- Master full-stack web development
- Understand database design and relationships
- Implement secure authentication systems
- Learn API development and integration
- Practice collaborative development using Git

## ✨ Key Features

### 🔐 **Authentication & Security**
- JWT-based secure authentication
- Role-based access control (RBAC)
- Password encryption using bcrypt
- Protected routes and middleware

### 👨‍⚕️ **Doctor Management**
- Personal dashboard with appointment overview
- Availability slot management
- Patient history access
- Digital prescription creation
- Appointment confirmation/rejection

### 👤 **Patient Management**
- Browse available doctors by specialization
- Real-time slot availability checking
- Easy appointment booking interface
- Appointment history tracking
- Prescription download functionality

### 🧑‍💼 **Admin Panel**
- User management (approve/suspend accounts)
- System analytics and reporting
- Doctor and patient oversight
- Platform configuration settings

### 📅 **Appointment System**
- Three-stage appointment lifecycle:
  - 🟡 **Pending** - Newly booked appointments
  - 🟢 **Confirmed** - Doctor-approved appointments
  - ✅ **Completed** - Finished consultations with prescriptions
- Automatic email notifications
- Cancellation management

### 💊 **Prescription Management**
- Digital prescription creation by doctors
- Secure prescription storage
- PDF download functionality for patients
- Prescription history tracking

## 🏗️ Project Structure

```
📁 Appointment-Booking-System/
├── 📁 backend/                    # Node.js Backend Server
│   ├── 📁 src/
│   │   ├── 📁 config/            # Database & app configuration
│   │   ├── 📁 controllers/       # Route handlers & business logic
│   │   ├── 📁 middlewares/       # Authentication & validation
│   │   ├── 📁 routes/           # API route definitions
│   │   ├── 📁 services/         # Business logic services
│   │   ├── 📁 utils/            # Utility functions
│   │   ├── 📄 app.js            # Express app configuration
│   │   └── 📄 server.js         # Server entry point
│   ├── 📁 prisma/
│   │   ├── 📁 migrations/       # Database migrations
│   │   └── 📄 schema.prisma     # Database schema definition
│   ├── 📄 package.json         # Backend dependencies
│   ├── 📄 .env                 # Environment variables
│   └── 📄 .env.example         # Environment template
│
├── 📁 frontend/                  # React.js Frontend Application
│   ├── 📁 src/
│   │   ├── 📁 components/       # Reusable React components
│   │   ├── 📁 pages/           # Page components
│   │   ├── 📁 hooks/           # Custom React hooks
│   │   ├── 📁 context/         # React context providers
│   │   ├── 📁 utils/           # Frontend utilities
│   │   ├── 📁 assets/          # Images, icons, styles
│   │   └── 📄 main.jsx         # React app entry point
│   ├── 📄 package.json         # Frontend dependencies
│   ├── 📄 vite.config.js       # Vite configuration
│   └── 📄 index.html           # HTML template
│
├── 📄 README.md                 # Project documentation (this file)
├── 📄 idea.md                   # Project planning & ideas
└── 📁 .git/                    # Git version control
```

## 💻 Tech Stack

### 🎨 **Frontend**
| Technology | Purpose | Version |
|------------|---------|---------|
| ![React](https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB) | UI Framework | ^19.1.1 |
| ![Vite](https://img.shields.io/badge/Vite-646CFF?logo=vite&logoColor=white) | Build Tool | ^7.1.2 |
| ![Axios](https://img.shields.io/badge/Axios-5A29E4?logo=axios&logoColor=white) | HTTP Client | ^1.12.2 |
| ![React Router](https://img.shields.io/badge/React_Router-CA4245?logo=react-router&logoColor=white) | Routing | ^7.9.1 |

### ⚙️ **Backend**
| Technology | Purpose | Version |
|------------|---------|---------|
| ![Node.js](https://img.shields.io/badge/Node.js-43853D?logo=node.js&logoColor=white) | Runtime Environment | Latest |
| ![Express](https://img.shields.io/badge/Express.js-404D59?logo=express&logoColor=white) | Web Framework | Latest |
| ![Prisma](https://img.shields.io/badge/Prisma-3982CE?logo=Prisma&logoColor=white) | ORM | ^6.16.3 |
| ![JWT](https://img.shields.io/badge/JWT-black?logo=JSON%20web%20tokens) | Authentication | ^9.0.2 |
| ![bcrypt](https://img.shields.io/badge/bcrypt-338?logo=npm&logoColor=white) | Password Hashing | ^6.0.0 |

### 🗄️ **Database**
| Technology | Purpose |
|------------|---------|
| ![MySQL](https://img.shields.io/badge/MySQL-00000F?logo=mysql&logoColor=white) | Primary Database |
| ![Prisma](https://img.shields.io/badge/Prisma-3982CE?logo=Prisma&logoColor=white) | Database ORM |

### 🛠️ **Development Tools**
| Tool | Purpose |
|------|---------|
| ![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white) | Version Control |
| ![ESLint](https://img.shields.io/badge/ESLint-4B3263?logo=eslint&logoColor=white) | Code Linting |
| ![Nodemon](https://img.shields.io/badge/Nodemon-76D04B?logo=nodemon&logoColor=white) | Development Server |

## ⚙️ Installation & Setup

### 📋 Prerequisites
Before you begin, ensure you have the following installed on your system:

- ![Node.js](https://img.shields.io/badge/Node.js-v18+-43853D?logo=node.js&logoColor=white) **Node.js** (v18 or higher)
- ![npm](https://img.shields.io/badge/npm-v8+-CB3837?logo=npm&logoColor=white) **npm** (v8 or higher) 
- ![MySQL](https://img.shields.io/badge/MySQL-v8+-00000F?logo=mysql&logoColor=white) **MySQL** (v8 or higher)
- ![Git](https://img.shields.io/badge/Git-latest-F05032?logo=git&logoColor=white) **Git** (latest version)

### 🔧 Step-by-Step Installation

#### 1️⃣ Clone the Repository
```bash
# Clone the project repository
git clone https://github.com/your-username/Appointment-Booking-System.git

# Navigate to the project directory
cd Appointment-Booking-System
```

#### 2️⃣ Backend Setup
```bash
# Navigate to backend directory
cd backend

# Install backend dependencies
npm install

# Create environment file from template
cp .env.example .env
```

#### 3️⃣ Configure Environment Variables
Edit the `.env` file in the backend directory:
```env
# Database Configuration
DATABASE_URL="mysql://username:password@localhost:3306/appointment_booking"

# JWT Secret (use a strong, random string)
JWT_SECRET="your-super-secret-jwt-key-here"

# Server Configuration
PORT=5000
NODE_ENV=development

# Email Configuration (optional)
EMAIL_HOST="smtp.gmail.com"
EMAIL_PORT=587
EMAIL_USER="your-email@gmail.com"
EMAIL_PASS="your-app-password"
```

#### 4️⃣ Database Setup
```bash
# Generate Prisma client
npx prisma generate

# Run database migrations
npx prisma migrate dev

# (Optional) Seed the database with sample data
npx prisma db seed
```

#### 5️⃣ Frontend Setup
```bash
# Navigate to frontend directory (from project root)
cd frontend

# Install frontend dependencies
npm install
```

## 🚀 How to Run

### 🖥️ Development Mode

#### 🔧 Start Backend Server
```bash
# In the backend directory
cd backend
npm run dev
```
The backend server will start on `http://localhost:3000`

#### 🎨 Start Frontend Application
```bash
# In a new terminal, navigate to frontend directory
cd frontend
npm run dev
```
The frontend application will start on `http://localhost:5173`

### 🌐 Access the Application
- **Frontend**: http://localhost:5173
- **Backend API**: http://localhost:3000
- **Database Studio**: `npx prisma studio` (run in backend directory)

### 🏗️ Production Build

#### Backend Production
```bash
cd backend
npm start
```

#### Frontend Production
```bash
cd frontend
npm run build
npm run preview
```

## 👤 User Roles

### 👨‍⚕️ **Doctor Role**
**Login Credentials**: `doctor@example.com` / `password123`

**Capabilities**:
- 📅 View and manage daily appointments
- ⏰ Set availability slots
- ✅ Confirm or reject appointment requests
- 💊 Create and manage prescriptions
- 👥 View patient history and details
- 📊 Access appointment analytics

### 👤 **Patient Role**
**Login Credentials**: `patient@example.com` / `password123`

**Capabilities**:
- 🔍 Browse doctors by specialization
- 📅 View available appointment slots
- 📝 Book new appointments
- 📋 View appointment history
- 💊 Download prescriptions
- ✏️ Update profile information

### 🧑‍💼 **Admin Role**
**Login Credentials**: `admin@example.com` / `password123`

**Capabilities**:
- 👥 Manage all users (patients & doctors)
- ✅ Approve or suspend user accounts
- 📊 View system analytics and reports
- ⚙️ Configure system settings
- 🗄️ Manage database records
- 📧 Send system notifications

## 🔗 API Endpoints

### 🔐 Authentication Routes
```http
POST   /api/auth/register     # User registration
POST   /api/auth/login        # User login
POST   /api/auth/logout       # User logout
GET    /api/auth/profile      # Get user profile
PUT    /api/auth/profile      # Update user profile
```

### 👨‍⚕️ Doctor Routes
```http
GET    /api/doctor/appointments     # Get doctor's appointments
POST   /api/doctor/slots           # Create availability slots
PUT    /api/doctor/slots/:id       # Update availability slot
DELETE /api/doctor/slots/:id       # Delete availability slot
POST   /api/doctor/prescription    # Create prescription
GET    /api/doctor/patients        # Get doctor's patients
```

### 👤 Patient Routes
```http
GET    /api/patient/doctors        # Get all doctors
GET    /api/patient/appointments   # Get patient's appointments
POST   /api/patient/book          # Book new appointment
PUT    /api/patient/appointments/:id # Update appointment
DELETE /api/patient/appointments/:id # Cancel appointment
GET    /api/patient/prescriptions  # Get patient's prescriptions
```

### 🧑‍💼 Admin Routes
```http
GET    /api/admin/users           # Get all users
PUT    /api/admin/users/:id       # Update user status
DELETE /api/admin/users/:id       # Delete user
GET    /api/admin/appointments    # Get all appointments
GET    /api/admin/analytics       # Get system analytics
```

### 📊 General Routes
```http
GET    /api/specializations      # Get all medical specializations
GET    /api/appointments/:id     # Get specific appointment
PUT    /api/appointments/:id     # Update appointment status
```

## 📸 Screenshots

### 🏠 Landing Page
![Landing Page](./screenshots/landing-page.png)

### 🔐 Login Page
![Login Page](./screenshots/login-page.png)

### 👤 Patient Dashboard
![Patient Dashboard](./screenshots/patient-dashboard.png)

### 👨‍⚕️ Doctor Dashboard
![Doctor Dashboard](./screenshots/doctor-dashboard.png)

### 🧑‍💼 Admin Panel
![Admin Panel](./screenshots/admin-panel.png)

## 🤝 Contributing

We welcome contributions from all team members! Please follow these guidelines:

### 📝 Development Workflow
1. **Create a new branch** for your feature:
   ```bash
   git checkout -b feature/your-feature-name
   ```

2. **Make your changes** and commit them:
   ```bash
   git add .
   git commit -m "Add: your descriptive commit message"
   ```

3. **Push to your branch**:
   ```bash
   git push origin feature/your-feature-name
   ```

4. **Create a Pull Request** on GitHub

### 📋 Code Standards
- Use meaningful variable and function names
- Add comments for complex logic
- Follow consistent indentation (2 spaces)
- Test your code before committing
- Update documentation when needed

### 🐛 Bug Reports
If you find a bug, please create an issue with:
- Clear description of the problem
- Steps to reproduce
- Expected vs actual behavior
- Screenshots (if applicable)

## 📄 License

This project is created for educational purposes as part of our college coursework. All rights reserved to the team members.

---

## 🎓 Academic Submission Notes

### 📚 Project Documentation
This project demonstrates our understanding of:
- Full-stack web development principles
- Database design and relationships
- RESTful API development
- User authentication and authorization
- Frontend-backend integration
- Version control with Git

### 🏆 Key Achievements
- ✅ Implemented secure user authentication
- ✅ Created responsive user interfaces
- ✅ Designed normalized database schema
- ✅ Built RESTful API endpoints
- ✅ Integrated frontend with backend
- ✅ Implemented role-based access control

### 📈 Future Enhancements
- 📱 Mobile application development
- 💳 Payment gateway integration
- 📧 Advanced email notification system
- 📊 Advanced analytics and reporting
- 🔔 Real-time notifications
- 🌐 Multi-language support

---

<div align="center">

### 🎯 Made with ❤️ by TheDevelopers.

**⭐ If you found this project helpful, please give it a star!**

[![GitHub stars](https://img.shields.io/github/stars/your-username/Appointment-Booking-System?style=social)](https://github.com/your-username/Appointment-Booking-System)
[![GitHub forks](https://img.shields.io/github/forks/your-username/Appointment-Booking-System?style=social)](https://github.com/your-username/Appointment-Booking-System)

</div>
