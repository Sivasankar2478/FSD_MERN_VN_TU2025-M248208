📘 DocSpot – Complete Doctor Appointment Booking System

DocSpot is a full-stack MERN application designed to simplify healthcare appointment management for both patients and doctors. The platform provides seamless booking, appointment tracking, doctor dashboards, authentication, and analytics.

🚀 Features
🧑‍⚕️ For Doctors

Login & secure authentication

Personalized doctor dashboard

View all appointments

Approve / Reject appointment requests

View upcoming appointments

Filter appointments by latest date

Doctor details & profile section

Analytics (appointments count, booking trends)

🧑‍💼 For Patients

User signup/login

Browse available doctors

Book appointments

View appointment details & status

Cancel bookings

Responsive UI for mobile & desktop

🔐 Authentication & Security

JWT-based authentication

Password hashing using bcrypt

Role-based access (doctor/user)

Protected routes (frontend & backend)

🏗️ Tech Stack
Frontend

React.js

Redux Toolkit (authentication state)

Axios

React Router

Tailwind CSS / CSS Modules

Backend

Node.js

Express.js

MongoDB + Mongoose

JWT Authentication

Bcrypt

Validator

📂 Folder Structure
DocSpot/
│── server/
│   ├── models/
│   ├── controllers/
│   ├── routes/
│   ├── middleware/
│   ├── config/
│   └── server.js
│
|---/Documentation
|
│── client/
│   ├── src/
│   ├── components/
│   ├── redux/
│   └── App.jsx
│
└── README.md

⚙️ Installation Guide
⭐ 1. Clone the repo
git clone https://github.com/Sivasankar2478/FSD_MERN_VN_TU2025-M248208
cd docspot

⭐ 2. Install backend dependencies
cd backend
npm install

⭐ 3. Install frontend dependencies
cd ../frontend
npm install

⭐ 4. Configure environment variables

Create a .env inside backend:

MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
PORT=5000

▶️ How to Run the Project
Run backend:
cd backend
nodemon  index.js

Run frontend:
cd frontend
npm run dev

