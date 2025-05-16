# 🔐 User Authentication System

A full-stack web application that enables users to sign up, log in, and access a protected profile page. Built with **Node.js**, **Express**, **MySQL**, and **Handlebars**, this project focuses on secure user authentication using **bcrypt** password hashing and session handling.

---

## 🔗 Live Demo

[![Live Demo](https://img.shields.io/badge/Demo-Live-blue?style=for-the-badge)](https://drive.google.com/file/d/1JXVJuFttKtwgQHi4oX1V4RvBA8xwemN8/view?usp=sharing)

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

├── index.js # Entry point – sets up the Express server <br>
├── db.js # MySQL connection configuration<br>
├── routes/<br>
│ └── auth.js # Handles signup, login, and logout routes<br>
├── views/<br>
│ ├── home.hbs # Home page template<br>
│ ├── login.hbs # Login page template<br>
│ ├── register.hbs # Registration page template<br>
│ └── profile.hbs # Protected profile page<br>
├── public/<br>
│ ├── style.css # Custom CSS styles<br>
│ └── avatar.png # Default user avatar<br>
├── .env # Environment variables (DB credentials)<br>
└── package.json # Project metadata and dependencies<br>
