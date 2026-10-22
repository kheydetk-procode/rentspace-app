# RentSpace - Room Rental Marketplace

A full-stack web application built with **Vue 3**, **Node.js (Express)**, and **MongoDB (NoSQL Database)** for listing and searching room rentals.

## 📁 Project Structure
```text
rentspace-app/
├── package.json
├── .env
├── server.js
└── public/
    └── index.html
```

## 🚀 Quick Start Instructions

1. **Install Dependencies:**
   ```bash
   npm install
   ```

2. **Configure Environment Variables:**
   Update `.env` with your MongoDB connection string from MongoDB Atlas:
   ```env
   PORT=5000
   MONGODB_URI=your_mongodb_connection_string
   JWT_SECRET=super_secret_jwt_key
   ```

3. **Run Application locally:**
   ```bash
   npm run dev
   # or
   npm start
   ```
   Open `http://localhost:5000` in your browser.
