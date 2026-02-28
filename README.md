# 🚀 HireHelper – On-Demand Task Assistance Application

HireHelper is a full-stack web application that connects users who need help with individuals willing to assist in completing tasks.  
The platform provides secure authentication, task posting, request management, notifications, and profile management in a structured dashboard interface.

---

## 📌 Project Overview

HireHelper simplifies everyday task coordination by enabling users to:

- Post tasks requiring assistance  
- Discover available tasks  
- Send and manage helper requests  
- Receive notifications  
- Maintain personalized user profiles  

The application follows a modern MERN-style architecture with secure authentication and scalable workflow management.

---

## 🏗️ Tech Stack

### 🔹 Frontend
- React.js
- Vite
- Tailwind CSS
- React Router DOM

### 🔹 Backend
- Node.js
- Express.js
- MongoDB
- Mongoose

### 🔹 Authentication & Security
- JWT Authentication
- OTP Email Verification
- bcrypt Password Hashing

### 🔹 Additional Tools
- Nodemailer (Email OTP)
- Multer (Image Uploads)
- Cloudinary (Media Storage Ready)
- UUID
- CORS & dotenv

---

## ✨ Features

- ✅ OTP-Based Secure Authentication  
- ✅ JWT Protected Routes  
- ✅ Task Posting & Management  
- ✅ Helper Request System  
- ✅ Task Feed Dashboard  
- ✅ Profile Management  
- ✅ Image Upload Support  
- ✅ Request Accept / Reject Workflow  
- ✅ Account Deletion  
- ✅ Responsive Dashboard UI  

---

## 📂 Project Structure
<pre>
HireHelper/
│
├── backend/
│ ├── src/
│ │ ├── controllers/
│ │ ├── models/
│ │ ├── routes/
│ │ ├── middleware/
│ │ ├── config/
│ │ └── utils/
│ └── index.js
│
├── frontend/
│ ├── src/
│ │ ├── components/
│ │ ├── pages/
│ │ ├── utils/
│ │ └── App.jsx
│ └── vite.config.js
│
└── README.md
</pre>


---

## 🔐 Authentication Flow

1. User registers using email.
2. OTP verification is sent via email.
3. Account gets verified after OTP validation.
4. JWT token generated on login.
5. Protected routes accessible using authentication token.

---

## 🔄 Application Workflow

### 📝 Task Owner
- Create tasks
- Manage posted tasks
- Accept or reject helper requests

### 🤝 Helper
- Browse available tasks
- Send task requests
- Track request status

---

## ⚙️ Installation & Setup

### 1️⃣ Clone Repository

```bash
git clone https://github.com/your-username/HireHelper-On-Demand-Task-Assistance-Application.git
cd HireHelper-On-Demand-Task-Assistance-Application
```
```bash
cd backend
npm install
```
```bash
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key

MAIL_USER=your_email@gmail.com
MAIL_PASS=your_app_password

CLOUDINARY_CLOUD_NAME=
CLOUDINARY_API_KEY=
CLOUDINARY_API_SECRET=
```
```bash
npm run dev
```
```bash
cd frontend
npm install
npm run dev
```
```bash
http://localhost:5173
```
```bash
http://localhost:5000
```
