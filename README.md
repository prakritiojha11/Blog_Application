# 📝 Blogging App - A Full-Stack Web Application

The **Blogging App** is a full-stack web application that allows users to **create, edit, delete, and read blog posts**. It features **secure user authentication using JWT**, an intuitive UI built with **EJS and CSS**, and a **MongoDB database** for storing blog posts and user details.  

This project demonstrates how to implement **user authentication, secure session management, image uploads, and a CRUD-based blogging system** using modern web development technologies.  

---

## 🌟 **Key Features**

### ✅ User Authentication & Security
- Secure **signup, login, and logout** using **JWT authentication**.
- **Password hashing** for security using the **crypto** library.
- **Middleware-based authentication check** for secure access.

### 📝 Blog Management
- **Create, Read, Update, and Delete (CRUD)** blogs.
- **Upload images** with blogs using **Multer**.
- **Responsive UI** with **EJS templates**.

### 📜 Comments Section
- Users can **comment on blog posts**.
- Comments stored in **MongoDB** and displayed dynamically.

### 📂 File Uploads & Static Files
- Users can upload images with blog posts.
- Static files such as images and CSS are handled using `express.static()`.

### ⚡ Performance & Optimization
- **Modular structure** with separate routes for users and blogs.
- **Efficient data handling** with **MongoDB** and **Mongoose**.
- **Optimized middleware for authentication and error handling**.

---

## 🛠 **Tech Stack Used**

| Technology | Purpose |
|------------|---------|
| **Frontend** | HTML, CSS, EJS |
| **Backend** | Node.js, Express.js |
| **Database** | MongoDB with Mongoose |
| **Authentication** | JWT (JSON Web Tokens) |
| **File Uploads** | Multer |
| **Middleware** | Express, Cookie-parser |

---

## 🚀 **Installation Guide**

### **1️⃣ Clone the repository**
First, clone this repository to your local machine:
```sh
git clone https://github.com/prakritiojha11/Blog_Application.git
cd Blog_Application
