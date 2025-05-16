# 🔐 User Authentication System

A full-stack web application that enables users to sign up, log in, and access a protected profile page. Built with **Node.js**, **Express**, **MySQL**, and **Handlebars**, this project focuses on secure user authentication using **bcrypt** password hashing and session handling.

---

## 🔗 Live Demo

[![Live Demo](https://img.shields.io/badge/Demo-Live-blue?style=for-the-badge)](https://your-demo-link.com)

---

## 🚀 Features

- User Registration with hashed passwords
- Secure Login & Logout functionality
- Protected Profile Page with avatar
- Session-based authentication
- Handlebars templating for frontend
- Responsive UI using Bootstrap
- Environmental variables for sensitive credentials

---

## 🛠️ Tech Stack

- **Backend:** Node.js, Express
- **Frontend:** Handlebars, HTML/CSS, Bootstrap
- **Database:** MySQL
- **Authentication:** bcrypt, express-session
- **Environment Config:** dotenv

---

## 📁 Project Structure

├── index.js # Entry point – sets up the Express server
├── db.js # MySQL connection configuration
├── routes/
│ └── auth.js # Handles signup, login, and logout routes
├── views/
│ ├── home.hbs # Home page template
│ ├── login.hbs # Login page template
│ ├── register.hbs # Registration page template
│ └── profile.hbs # Protected profile page
├── public/
│ ├── style.css # Custom CSS styles
│ └── avatar.png # Default user avatar
├── .env # Environment variables (DB credentials)
└── package.json # Project metadata and dependencies
