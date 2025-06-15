README.md

# 🏫 Mackdish School Management System

A full-stack school management system for managing students, fees, attendance, exams, academic reports, and user roles. Designed with modern UI/UX using React, Tailwind UI, and Node.js.

## ✨ Features

- 🔐 Role-Based Login (Admin, Clerk, Principal)
- 👨‍🎓 Student Registration and Filtering (by Class, Name)
- 💰 Fee Management (payments, balances, filtering by date or student)
- 📊 Dashboard Analytics (charts for fees, students, and activity logs)
- 📅 Attendance Tracking (mark and view daily attendance)
- 📝 Exam Module (record scores, view academic reports)
- 🔁 Password Reset Flow via Email
- 📲 SMS Notifications (via Africa’s Talking)
- 💵 M-Pesa STK Push Integration (school fees)
- 🌑 Dark Mode UI
- 📱 Mobile Responsive Frontend

## 🛠️ Tech Stack

### Frontend
- React JS
- Tailwind CSS (UI)
- React Router DOM
- Axios
- Firebase Hosting

### Backend
- Node.js
- Express.js
- MongoDB (MongoDB Atlas)
- JWT Authentication
- Render Hosting

---

## 📁 Project Structure

mackdish-school-system/ │ ├── backend/          # Node.js backend (Express + MongoDB) │   ├── models/ │   ├── routes/ │   ├── controllers/ │   ├── .env.example │   └── README.md │ ├── frontend/         # React frontend (Tailwind UI) │   ├── src/ │   ├── .env.example │   └── README.md

## ⚙️ Setup Instructions

### 🔧 Backend Setup

1. Clone repo and install dependencies:

```bash
cd backend
npm install

2. Create .env file using .env.example:

MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key

3. Start the server:

node index.js

🌐 Frontend Setup

1. Navigate to frontend and install dependencies:

cd frontend
npm install

2. Create .env using the example:

REACT_APP_API_BASE_URL=https://your-backend-url.onrender.com/api

3. Start the frontend:

npm start

🚀 Deployment

Backend:

Deployed on Render

Frontend:

Hosted on Firebase Hosting

🔒 Login Roles

Role	Access Level

Admin	Full Access
Clerk	Student & Fee Management
Principal	View-only Reports & Dashboard

Default login credentials can be updated in the backend database

📬 Contact

For support or custom setup, contact:

MACKDISH SOLUTIONS
📧 macknonvulimu708@gmail.com
📍 Mbale, Kenya
📞 +254 705 186 502
