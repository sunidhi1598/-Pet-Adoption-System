Pet Adoption Management System
Project Description

This is a full stack web application built using the MERN stack (MongoDB, Express, React, Node.js). The application allows visitors to browse pets available for adoption, users to submit adoption requests, and administrators to manage adoption applications.

This project demonstrates frontend development, backend API creation, authentication, and database integration.

Live Links

Frontend (User Interface)

https://petadoptionsystemm.netlify.app

Backend API

https://pet-adoption-system-8duc.onrender.com

GitHub Repository

https://github.com/sunidhi1598/-Pet-Adoption-System
Technologies Used

Frontend
React
Axios
Bootstrap

Backend
Node.js
Express.js
JWT Authentication

Database
MongoDB

Features
Visitor

View list of available pets

Search pets by name

Filter pets by species

View pet details

Pagination on pet list

User

Register and login

Apply to adopt available pets

View personal adoption applications and status

Admin

View all adoption applications

Approve or reject adoption requests

Pet status automatically updates after approval

Project Structure
pet-adoption-system
│
├── backend
│   ├── models
│   ├── routes
│   ├── middleware
│   └── server.js
│
├── frontend
│   ├── src
│   ├── components
│   ├── pages
│   └── App.js
│
└── README.md
Running the Project Locally
Backend
cd backend
npm install
npm start

Create a .env file with:

PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
Frontend
cd frontend
npm install
npm start

The application will run at:
http://localhost:3000


Author
Sunidhi Kumari
