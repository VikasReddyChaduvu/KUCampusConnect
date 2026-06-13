# Campus Connect

![Status](https://img.shields.io/badge/Status-Active-brightgreen)
![License](https://img.shields.io/badge/License-MIT-blue.svg)
![React](https://img.shields.io/badge/React-19-blue.svg)
![Node.js](https://img.shields.io/badge/Node.js-Express-green.svg)
![MongoDB](https://img.shields.io/badge/MongoDB-Database-green.svg)
![JWT](https://img.shields.io/badge/JWT-Authentication-orange.svg)

**Campus Connect** is a full-stack social networking platform designed specifically for educational institutions. It provides a secure and collaborative environment where students, faculty, and administrators can interact, share updates, join groups, and manage campus events.

---

## 🌐 Live Demo

Frontend: Coming Soon

Backend API: Coming Soon

---

## 📸 Screenshots

### Login Page

![Login](screenshots/login.png)

### Dashboard

![Dashboard](screenshots/dashboard.png)

### Campus Feed

![Feed](screenshots/feed.png)

### Events Section

![Events](screenshots/events.png)

---

## 🚀 Features

### 🔐 Authentication & Security

* JWT-based Authentication
* Secure Password Hashing using bcrypt
* Role-Based Access Control
* Protected Routes

### 👥 User Management

* Student Profiles
* Faculty Profiles
* Administrator Controls
* Profile Updates

### 📝 Campus Feed

* Create Posts
* Share Updates
* Upload Images
* Like and Interact with Content

### 👨‍👩‍👧‍👦 Group Management

* Create Groups
* Join Groups
* Manage Group Members
* Academic & Interest-Based Communities

### 📅 Event Management

* Create Campus Events
* Manage Event Details
* Event Discovery
* Participation Tracking

### 📧 Notifications

* Password Recovery Emails
* Account Notifications
* Email Integration using Nodemailer

### 📱 Responsive Design

* Mobile-Friendly UI
* Modern User Experience
* Responsive Layouts

---

## 🏗️ System Architecture

```text
User
  │
  ▼
React Frontend
  │
  ▼
Express.js API
  │
  ▼
MongoDB Database
```

---

## 💻 Tech Stack

### Frontend

* React.js
* Vite
* Tailwind CSS
* React Router v7
* Axios

### Backend

* Node.js
* Express.js

### Database

* MongoDB
* Mongoose

### Authentication

* JWT (jsonwebtoken)
* bcryptjs

### Additional Tools

* Multer
* Nodemailer

---

## 📁 Project Structure

```text
KUCampusConnect/
│
├── client/
│   ├── src/
│   ├── public/
│   └── package.json
│
├── server/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── uploads/
│   └── package.json
│
├── README.md
└── .gitignore
```

---

## 📋 Prerequisites

Before running the project, ensure you have:

* Node.js (v16 or higher)
* MongoDB (Local or Atlas)
* Git

---

## 🛠️ Installation & Setup

### 1. Clone Repository

```bash
git clone https://github.com/VikasReddyChaduvu/KUCampusConnect.git
cd KUCampusConnect
```

---

### 2. Backend Setup

Navigate to the server directory:

```bash
cd server
npm install
```

Create a `.env` file:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
EMAIL_USER=your_email
EMAIL_PASS=your_email_password
```

Start the backend server:

```bash
npm run dev
```

Backend runs on:

```text
http://localhost:5000
```

---

### 3. Frontend Setup

Open a new terminal:

```bash
cd client
npm install
```

Create a `.env` file:

```env
VITE_API_BASE_URL=http://localhost:5000/api
```

Run the frontend:

```bash
npm run dev
```

Frontend runs on:

```text
http://localhost:5173
```

---

## 📚 What I Learned

Through this project, I gained practical experience in:

* MERN Stack Development
* REST API Design
* JWT Authentication
* MongoDB Data Modeling
* Role-Based Access Control
* File Upload Management
* Email Service Integration
* Full-Stack Application Development
* Git & GitHub Workflow

---

## 🚀 Future Enhancements

* Real-Time Chat using Socket.IO
* Push Notifications
* Video Conferencing
* Mobile Application
* AI-Based Recommendations
* Advanced Search & Filtering
* Event Analytics Dashboard

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome.

1. Fork the repository
2. Create a feature branch

```bash
git checkout -b feature/AmazingFeature
```

3. Commit your changes

```bash
git commit -m "Add Amazing Feature"
```

4. Push to GitHub

```bash
git push origin feature/AmazingFeature
```

5. Open a Pull Request

---

## 📝 License

Distributed under the MIT License.

---

## ⭐ Support

If you found this project useful, consider giving it a star on GitHub.

⭐ Star the repository to support the project.
