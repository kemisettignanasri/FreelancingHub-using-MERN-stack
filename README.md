# 🚀 FreelanceHub

FreelanceHub is a full-stack MERN web application that connects freelancers with employers. The platform enables employers to post jobs, manage applications, and hire skilled professionals, while freelancers can create professional profiles, search for jobs, apply for opportunities, and track their application status.

Built using the **MERN Stack (MongoDB, Express.js, React.js, Node.js)**, the application provides a secure, scalable, and user-friendly freelancing platform.

---

## 📌 Features

### 👨‍💼 Employer
- Register and Login
- Secure JWT Authentication
- Create and manage job postings
- View freelancer profiles
- Accept or reject applications
- Edit employer profile
- Track applicant status

### 👩‍💻 Freelancer
- Register and Login
- Secure JWT Authentication
- Create and update profile
- Upload professional portfolio
- Search available jobs
- Apply for jobs
- Track application status
- Edit uploaded profile

---

## 🛠️ Tech Stack

### Frontend
- React.js
- React Router
- React Hook Form
- Bootstrap
- CSS
- React Icons

### Backend
- Node.js
- Express.js
- JWT Authentication
- bcrypt.js

### Database
- MongoDB

### Tools
- Git & GitHub
- VS Code
- Postman

---

## 📂 Project Structure

```
FreelanceHub/
│
├── client/
│   ├── src/
│   ├── public/
│   └── package.json
│
├── server/
│   ├── APIs/
│   ├── middleware/
│   ├── config/
│   ├── package.json
│   └── server.js
│
└── README.md
```

---

## 🔐 Authentication

- JWT (JSON Web Token)
- Password Hashing using bcrypt.js
- Role-based Authentication
  - Employer
  - Freelancer

---

## ⚙️ Installation

### Clone the repository

```bash
git clone https://github.com/your-username/FreelanceHub.git
```

Move into the project

```bash
cd FreelanceHub
```

---

### Install Frontend

```bash
cd client
npm install
npm start
```

---

### Install Backend

```bash
cd server
npm install
npm run dev
```

---

## 🌐 Environment Variables

Create a `.env` file inside the server folder.

```env
PORT=4000

MONGO_URI=Your_MongoDB_Connection_String

SECRET_KEY=Your_JWT_Secret
```

---

## 📸 Screenshots

You can add screenshots here.

Example:

- Home Page
- Login
- Register
- Employer Dashboard
- Freelancer Dashboard
- Job Listings
- Profile Page

---

## ✨ Future Enhancements

- Real-time Chat
- Payment Gateway Integration
- Notifications
- Resume Upload
- AI-based Job Recommendations
- Email Verification
- Forgot Password
- Admin Dashboard

---



