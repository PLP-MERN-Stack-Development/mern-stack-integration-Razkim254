# 📝 MERN Blog Application

![Node.js](https://img.shields.io/badge/Node.js-v18+-green)
![MongoDB](https://img.shields.io/badge/MongoDB-Atlas%20or%20Local-brightgreen)
![React](https://img.shields.io/badge/React-Vite-blue)
![License](https://img.shields.io/badge/License-MIT-yellow)

A full-stack blog platform built with the MERN stack (MongoDB, Express.js, React.js, Node.js). This project demonstrates seamless integration between front-end and back-end components, including database operations, RESTful APIs, and state management.

---

## 🚀 Project Overview

This application allows users to:
- View a list of blog posts
- Read individual posts
- Create, edit, and delete posts
- Manage categories
- (Advanced) Register/login, upload images, paginate posts, and add comments

Built with:
- **MongoDB** for data storage
- **Express.js** for backend API
- **React.js** with Vite for frontend
- **Node.js** for server runtime

---

## 📁 Directory Structure

mern-blog/ ├── client/ # React frontend (Vite) │ ├── src/ │ │ ├── components/ │ │ ├── pages/ │ │ ├── hooks/ │ │ ├── services/ │ │ └── App.jsx │ ├── public/ │ └── vite.config.js ├── server/ # Express backend │ ├── controllers/ │ ├── models/ │ ├── routes/ │ ├── middleware/ │ ├── config/ │ └── server.js ├── .env.example # Environment variable templates ├── README.md # Project documentation

Code

---

## 🛠️ Setup Instructions

### Prerequisites
- Node.js v18+
- MongoDB (local or Atlas)

### Clone the Repository
```bash
git clone https://github.com/YOUR_USERNAME/mern-blog-app.git
cd mern-blog-app
Install Server Dependencies
bash
cd server
npm install
Install Client Dependencies
bash
cd ../client
npm install
Configure Environment Variables
Create .env files in both client/ and server/ based on the provided .env.example.

server/.env
Code
MONGO_URI=your_mongodb_connection_string
PORT=5000
JWT_SECRET=your_jwt_secret
client/.env
Code
VITE_API_URL=http://localhost:5000
▶️ Running the App
Start Backend
bash
cd server
npm run dev
Start Frontend
bash
cd client
npm run dev
Visit: http://localhost:5173

📡 API Documentation
Posts
Method	Endpoint	Description
GET	/api/posts	Get all posts
GET	/api/posts/:id	Get a single post
POST	/api/posts	Create a post
PUT	/api/posts/:id	Update a post
DELETE	/api/posts/:id	Delete a post
Categories
Method	Endpoint	Description
GET	/api/categories	Get all categories
POST	/api/categories	Create a category
🧩 Features Implemented
✅ RESTful API with Express and MongoDB

✅ React frontend with Vite

✅ React Router for navigation

✅ Custom hooks for API calls

✅ Form validation

✅ Optimistic UI updates

✅ Error and loading states

✅ JWT-based authentication (Advanced)

✅ Image uploads (Advanced)

✅ Pagination and search (Advanced)

✅ Comments system (Advanced)

📸 Screenshots
🏠 Home Page

📝 Post View

✍️ Create/Edit Form

📄 License
This project is licensed under the MIT License. See the LICENSE file for details.

🤝 Contributing
Contributions are welcome! To contribute:

Fork the repo

Create a feature branch

Commit your changes

Open a pull request

Please follow the existing code style and include tests if applicable.
