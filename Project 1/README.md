Vetri Nichiyam – MERN Stack Project (TheSmartBridge)

📚 BOOK STORE

  This repository contains a full-stack MERN application developed as part of The SmartBridge Vetri Nichiyam.
  The project includes complete frontend and backend integration with authentication, product management, cart system, order handling, and seller features.

🚀 Tech Stack
Frontend

React.js

Redux Toolkit

Bootstrap

Axios

Backend

Node.js

Express.js

MongoDB + Mongoose

JWT Authentication

Bcrypt

Multer (for images)

🛠 Features Implemented
👤 User Side

User Registration & Login (JWT)

View Books

Add to Cart

Buy Now

Place Orders

View Order History

🧾 Seller Side

Add Books

Delete Books

Manage My Products

🛒 Cart System

Add / Remove Items

Auto-update total price

Checkout with delivery charges

📂 Project Structure
/project
│── /client     # React frontend
│── /server     # Node + Express backend
|---/Documentation
│── package.json
│── README.md

⚙️ Setup Instructions
1️⃣ Clone the repository
git clone https://github.com/Sivasankar2478/FSD_MERN_VN_TU2025-M248208
cd vetrinichiyam-mern-project

2️⃣ Install dependencies
For backend:
cd server
npm install

For frontend:
cd client
npm install

3️⃣ Setup .env file in server
MONGO_URI=your_mongo_url
JWT_SECRET=your_secret
CLOUDINARY_KEY=optional


4️⃣ Run Backend
cd server
npm start

5️⃣ Run Frontend
cd client
npm start

6️⃣ After project running successfully .Go to your mongodb compass uploads booksStore.json file from this repo into your books collection.

📌 Work Pending / Future Enhancements

Add seller dashboard analytics

Add product categories filter

Improve cart UI

Integrate online payment gateway

Create admin panel for full control

🎉 Conclusion

This MERN application is a complete real-world style project demonstrating full-stack development skills with authentication,  MongoDB, and REST API integration.
