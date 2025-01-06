# Employee Management Frontend 🌟

Welcome to the **Employee Management System Frontend**, your comprehensive platform for managing employee information, tracking attendance, handling leaves, and monitoring projects with ease. Built with modern tools and designed for efficiency, this frontend application connects seamlessly with the backend to deliver an exceptional user experience.

---

## ✨ Key Features

### 🚀 Employee-Centric Dashboard
- Access detailed employee information, attendance logs, leave statuses, and project assignments in one place.

### 🖼️ Personalized Profiles
- Update profile pictures and personal details effortlessly.

### ⏱️ Smart Attendance Tracker
- Record daily attendance and view logs in a simple and intuitive interface.

### 🏝️ Leave Management Made Easy
- Apply for leave, monitor approval statuses, and access leave history.

### 👥 Explore the Directory
- Browse and search for employees across the organization.

### 📁 Efficient Project Management
- Track progress and view details for ongoing projects.

### 🔐 Secure Authentication
- Protect user data with JWT-based login authentication.

### 📱 Responsive Design
- Enjoy a seamless experience across all devices – desktop, tablet, or mobile.

---

## 💡 Tech Highlights

- **React**: The core framework for building dynamic UI components.
- **Redux**: Manage state globally for authentication, employee data, and more.
- **Axios**: Efficient API interaction for smooth communication with the backend.
- **React Router**: Simplified navigation between multiple views.
- **Bootstrap**: Elegant styling and responsive layouts.
- **Netlify**: Deployed for fast, reliable hosting.

---

## 🔗 API Integration

The frontend interacts with a powerful backend API deployed on Render. Below are some of the key endpoints it uses:

### **Authentication**
- **POST** `/api/auth/login`: Authenticate users and receive JWT tokens.

### **Employee Management**
- **GET** `/api/user/getemployee`: Retrieve employee data.
- **GET** `/api/user/getprofilepicture`: Fetch profile pictures.

### **Attendance**
- **POST** `/api/user/attendance/attendancerecord`: Get attendance logs.
- **POST** `/api/user/attendance/toggleswipestatus`: Mark or update attendance status.

### **Leave Management**
- **GET** `/api/user/leave`: View leave history.
- **POST** `/api/user/applyleave`: Submit leave requests.

---

## 🌍 Deployed Application

**Frontend URL**: [Employee Management Frontend](https://ems-vj08-frontend-task.netlify.app)

Explore the live application and experience how the Employee Management System works.

---

## 📢 Getting Started

To get the project running locally, follow these steps:

### Prerequisites:
- Node.js installed.
- Backend API running and accessible.

### Setup:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/employee-management-frontend.git
   cd employee-management-frontend
