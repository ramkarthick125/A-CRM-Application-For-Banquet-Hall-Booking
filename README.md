# 🎉 A-CRM-Application-For-Banquet-Hall-Booking

A full-stack **Banquet Hall Booking CRM Application** designed to streamline event management, customer interactions, and booking processes. Built using modern web technologies and inspired by CRM principles, this system provides a seamless experience for both administrators and customers.

---

## 📌 Project Overview

Managing banquet hall bookings manually can lead to errors such as:

* Double bookings
* Poor customer tracking
* Inefficient communication

This application provides a **centralized, automated solution** to handle bookings, events, customers, and analytics efficiently.

---

## 🚀 Features

### 🔐 Authentication & Security

* User registration and login
* Secure password hashing
* JWT-based authentication
* Role-based access (Admin & Customer)
* Protected routes

### 📅 Smart Booking System

* Real-time hall availability
* Instant booking confirmation
* Booking history tracking
* Event scheduling dashboard

### 🏢 Hall Management

* Multiple halls support
* Capacity and pricing management
* Availability tracking
* Hall details & amenities

### 🎉 Event Management

* Event types (Wedding, Birthday, Corporate)
* Guest count tracking
* Custom event planning
* Event workflow management

### 🍽️ Catering & Services

* Menu selection system
* Custom catering options
* Add-ons (Decoration, Photography, Music)
* Package-based services

### 👥 Customer Management

* Profile management
* Booking history
* Feedback system
* Personalized preferences

### 📊 Reports & Analytics

* Booking trends
* Revenue tracking
* Peak booking times
* Customer insights
* Exportable reports

### 🎨 UI/UX

* Responsive design (Mobile + Desktop)
* Clean and modern interface
* Smooth navigation
* User-friendly dashboards

---

## 🏗️ Tech Stack

### 💻 Frontend

* React.js
* HTML5, CSS3, JavaScript

### ⚙️ Backend

* Node.js
* Express.js
* REST API

### 🗄️ Database

* MongoDB

### 🔐 Authentication

* JSON Web Tokens (JWT)

---

## 📂 Project Structure

```
Banquet-Booking-System/
│
├── backend/
│   ├── app.js
│   ├── config.js
│   ├── models/
│   ├── routes/
│   └── controllers/
│
├── frontend/
│   ├── components/
│   ├── pages/
│   ├── css/
│   └── js/
│
├── package.json
└── README.md
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/banquet-booking-crm.git
cd banquet-booking-crm
```

### 2️⃣ Install Dependencies

```bash
# Backend
cd backend
npm install

# Frontend
cd ../frontend
npm install
```

### 3️⃣ Configure Environment Variables

Create a `.env` file in the backend folder:

```
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

### 4️⃣ Run the Application

```bash
# Start backend
cd backend
npm start

# Start frontend
cd ../frontend
npm start
```

---

## 🔗 API Endpoints

### Authentication

* `POST /api/auth/register`
* `POST /api/auth/login`

### Bookings

* `GET /api/bookings`
* `POST /api/bookings`
* `PUT /api/bookings/:id`
* `DELETE /api/bookings/:id`

### Events

* `GET /api/events`
* `POST /api/events`

---

## 📖 Usage Guide

1. Register / Login
2. Check hall availability
3. Create booking
4. Customize event (services & catering)
5. Confirm booking
6. Admin manages bookings & analytics

---

## 🔄 Real-Time Features

* Live availability updates
* Instant booking confirmation
* Dynamic dashboard updates

---

## 🧪 Testing

* Unit Testing
* Integration Testing
* Manual UI Testing

---

## 🐛 Troubleshooting

| Issue              | Solution                        |
| ------------------ | ------------------------------- |
| Server not running | Check Node.js installation      |
| Database error     | Ensure MongoDB is running       |
| Login issues       | Verify JWT secret & credentials |

---

## 📈 Future Enhancements

* Online payment integration
* Email & SMS notifications
* AI-based recommendations
* Multi-language support
* Mobile app version

---

## 📚 Learning Resources

* Node.js Documentation
* React.js Documentation
* MongoDB Documentation

---

## 📝 License

This project is developed for **educational and practical purposes**.

---
