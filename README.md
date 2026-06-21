# 🌌 E. Horizon

A full-stack event management and ticket booking platform built using **React, Node.js, Express, and MongoDB**. E. Horizon enables users to discover events, book tickets, and manage bookings through secure OTP-based authentication and role-based access control.

## 🚀 Live Demo

🔗 https://e-horizon.vercel.app

---

## ✨ Features

### 👤 User Features

* User Registration & Login
* Email OTP Verification
* JWT-Based Authentication
* Browse Available Events
* Search Events
* Filter Events by Category
* View Detailed Event Information
* Book Event Tickets
* View Booking History
* Responsive UI for Desktop & Mobile

### 🛠️ Admin Features

* Create New Events
* Update Existing Events
* Delete Events
* Manage Event Details
* Track Available Seats
* Monitor Bookings
* Confirm or Cancel Bookings

### 🔒 Security Features

* Password Hashing using bcrypt
* JWT Authentication
* OTP Email Verification
* Protected Routes
* Role-Based Access Control (RBAC)

---

## 🏗️ Tech Stack

### Frontend

* React.js
* Vite
* React Router DOM
* Axios
* Tailwind CSS
* React Icons

### Backend

* Node.js
* Express.js

### Database

* MongoDB
* Mongoose

### Authentication & Security

* JWT (JSON Web Tokens)
* bcrypt.js
* Email OTP Verification

### Email Service

* Nodemailer

### Deployment

* Frontend: Vercel
* Backend: Render
* Database: MongoDB Atlas

---

## 📸 Screenshots

> Add screenshots of your application here.

### Home Page

![Home Page](./screenshots/home.png)

### Event Details

![Event Details](./screenshots/event-details.png)

### Admin Dashboard

![Admin Dashboard](./screenshots/admin-dashboard.png)

---

## 🏛️ System Architecture

```text
React Frontend
      │
      ▼
 Axios API Calls
      │
      ▼
 Express Backend
      │
      ▼
 MongoDB Database
```

---

## 📂 Project Structure

```text
E-Horizon
│
├── client
│   ├── src
│   │   ├── components
│   │   ├── context
│   │   ├── pages
│   │   └── utils
│   └── package.json
│
├── server
│   ├── controllers
│   ├── middleware
│   ├── models
│   ├── routes
│   ├── utils
│   └── package.json
│
└── package.json
```

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/<your-username>/E-Horizon.git
cd E-Horizon
```

### Install Dependencies

```bash
npm run install:all
```

### Run Development Server

```bash
npm run dev
```

### Frontend

```text
http://localhost:5173
```

### Backend

```text
http://localhost:5000
```

---

## 🔑 Environment Variables

Create a `.env` file inside the `server` directory.

```env
PORT=5000

MONGO_URI=your_mongodb_connection_string

JWT_SECRET=your_jwt_secret

EMAIL_USER=your_email

EMAIL_PASS=your_email_password
```

---

## 🔗 API Endpoints

### Authentication

```http
POST /api/auth/register
POST /api/auth/login
POST /api/auth/verify-otp
```

### Events

```http
GET    /api/events
GET    /api/events/:id
POST   /api/events
PUT    /api/events/:id
DELETE /api/events/:id
```

### Bookings

```http
POST   /api/bookings/send-otp
POST   /api/bookings
GET    /api/bookings/my
PUT    /api/bookings/:id/confirm
DELETE /api/bookings/:id
```

---

## 📊 Core Modules

### Authentication Module

* User Registration
* User Login
* OTP Verification
* JWT Generation
* Protected Routes

### Event Management Module

* Create Event
* Update Event
* Delete Event
* Event Search & Filtering
* Event Details View

### Booking Module

* Ticket Booking
* Seat Availability Tracking
* Booking History
* Booking Confirmation

---

## 💡 Key Learnings

* Building RESTful APIs using Express.js
* JWT Authentication & Authorization
* OTP-based Email Verification
* MongoDB Data Modeling with Mongoose
* Role-Based Access Control
* Full-Stack Application Deployment
* Secure User Authentication Practices

---

## 🎯 Future Enhancements

* Online Payment Gateway Integration
* QR Code-Based Tickets
* Event Reviews & Ratings
* Event Analytics Dashboard
* Real-Time Notifications
* Social Media Sharing
* Multi-Admin Support

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome.

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push the branch
5. Open a Pull Request

---

## 👨‍💻 Contributors

### Mrinal Chaubey

* GitHub: https://github.com/MrinalChaubey

### Ishant Singh

* GitHub: https://github.com/IshantSingh27

---

## ⭐ Support

If you found this project helpful, please consider giving it a **Star ⭐** on GitHub.

It helps others discover the project and motivates further development.


Project: E. Horizon

If you like this project, consider giving it a ⭐ on GitHub.
