# User_Authentication_Sys

# User Authentication System (MERN Stack)  

## 📌 Assignment Overview
This project is a **JWT-based User Authentication System** built with **Express.js** and **MongoDB**. It includes **user signup, login, and protected routes**, ensuring secure access using **JSON Web Tokens (JWT)**.

---

## 🚀 Features
✅ User Signup (with email & password validation)  
✅ User Login (JWT token generation)  
✅ Protected Routes (only logged-in users can access)  
✅ Password Hashing using **bcrypt.js**  
✅ Input Validation & Error Handling  
✅ Built with **Express.js & MongoDB**  

---

## 🛠️ Tech Stack
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB (Mongoose)  
- **Authentication:** JWT (jsonwebtoken), bcrypt.js  
- **Validation:** express-validator  
- **Environment Variables:** dotenv  

---

## 📂 Project Structure
mern-auth/ │── server/ │ ├── config/ # Database connection │ ├── controllers/ # Authentication logic │ ├── middlewares/ # JWT authentication middleware │ ├── models/ # User schema (Mongoose) │ ├── routes/ # API routes │ ├── .env # Environment variables (ignored in Git) │ ├── .gitignore # Ignore node_modules, .env, logs │ ├── package.json # Dependencies │ ├── server.js # Main entry point │── README.md

## Error Handling & Validation
Uses express-validator for input validation.
Proper error messages for missing/invalid fields.

