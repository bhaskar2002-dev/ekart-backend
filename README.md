# Ekart – MERN Stack E-commerce Application

**Ekart** is a full-stack e-commerce application built using the **MERN stack (MongoDB, Express.js, React.js, Node.js)**. This project demonstrates a complete online shopping experience with secure authentication, product management, shopping cart, order processing, and payment integration.

---

## Backend Overview

The backend of **Ekart** is built using **Node.js, Express.js, and MongoDB**, providing a robust and scalable server for a full-featured e-commerce application. It handles **user authentication with JWT**, **role-based access control**, and **OTP-based email verification** for secure account management.

Product and cart operations are fully supported, allowing admins to manage products and users to browse, add to cart, and adjust quantities. **Cloudinary integration** with a custom **DataURI utility** enables efficient image storage and file handling, while **Multer middleware** ensures smooth uploads.

The backend also manages **orders and payment processing**, with **Razorpay integration** for secure online transactions and payment verification. **RESTful API design** ensures clean, maintainable code, and **Mongoose models** enforce data validation, relationships, and integrity across `User`, `Product`, `Cart`, `Order`, and `Session` collections.

Overall, the backend is designed for **security, scalability, and maintainability**, demonstrating practical expertise in **MERN stack development**, API design, and payment gateway integration.

---

## Features

- **User Authentication & Authorization** (JWT, OTP email verification)  
- **Product Management** (Add, Update, Delete, View Products)  
- **Cart Management** (Add, Update, Remove Items)  
- **Order Management** (Place Orders, View Order History)  
- **Payment Integration** with **Razorpay**  
- **Image Upload & Storage** with **Cloudinary & Multer**  
- **Middleware & Utilities** for secure and efficient backend operations  

---

## Tech Stack

| Frontend        | Backend        | Database        | Other Tools / Libraries        |
|-----------------|----------------|----------------|--------------------------------|
| React.js        | Node.js        | MongoDB         | Razorpay API                   |
| Redux / Context | Express.js     | Mongoose        | Cloudinary                     |
| Tailwind CSS / Bootstrap | JWT Auth |                | Nodemailer (Email OTP)         |
| React Router    |                |                | Multer (File Upload)           |

---

## Project Structure (Backend)

