# 🌍 Wanderlust

Wanderlust is a full-stack rental listing web application. Users can browse, create, update, and delete campground-style listings with image uploads, descriptions, and location details. It features secure authentication, user-friendly design, and full CRUD functionality.

---

## 🚀 Live Demo

🔗 **[View the Deployed App](https://wanderlust-hzkh.onrender.com/)**  

---

## 🖼️ Features

- 🏕️ Full CRUD for campgrounds (Create, Read, Update, Delete)
- 📸 Upload multiple images using Cloudinary
- 🔐 User authentication & session handling (Passport.js)
- 🗺️ Mapbox integration for interactive location display
- 💬 User-generated reviews and ratings
- 🌐 Responsive UI with EJS templating
- 🧼 Data validation and error handling
- 🧭 Navigation and flash messages for UX

---

## 🛠️ Tech Stack

- **Frontend**: HTML5, CSS3, JavaScript, EJS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB, Mongoose
- **Authentication**: Passport.js (Local Strategy)
- **File Uploads**: Cloudinary
- **Map Integration**: Mapbox GL JS
- **Templating**: EJS & EJS-Mate
- **Styling**: Bootstrap 5

---

## 🗂️ Folder Structure

```bash
wanderlust/
├── models/           # Mongoose schemas for Campground, User, Review
├── routes/           # Express route handlers (campgrounds, reviews, users)
├── public/           # Static assets (CSS, JS, images)
├── views/            # EJS templates
├── middleware/       # Reusable auth & validation middlewares
├── utils/            # Custom error handling, validation schemas
├── app.js            # Entry point of the application
├── package.json      # Project metadata and dependencies
└── README.md         # You're here!
