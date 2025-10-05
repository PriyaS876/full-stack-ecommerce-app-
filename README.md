# full-stack-ecommerce-app-
A complete **full-stack e-commerce web application** built using the **MERN Stack (MongoDB, Express.js, React, Node.js)**.  
This project demonstrates modern web development practices with a secure backend, responsive UI, and dynamic product management features.

# Overview
The **FullStack E-commerce App** provides an end-to-end shopping experience, including user authentication, product browsing, cart management, and order placement.  
It is designed to showcase full-stack development skills — from building RESTful APIs to creating an intuitive frontend interface.

# Features

- User Authentication & Authorization (JWT-based login/signup)
- Product Listing & Filtering
- Add to Cart & Checkout System
- Admin Dashboard(Add, Update, Delete Products)
- Product Image Upload & Management
- Responsive UI for all screen sizes
- RESTful API Integration
- Real-time Alerts / Toast Notifications


# Tech Stack

**Frontend**
- React.js  
- Redux Toolkit (State Management)  
- Axios (API Communication)  
- Tailwind CSS / Bootstrap  
**Backend**
- Node.js  
- Express.js  
- MongoDB (Database)  
- Mongoose (ODM)  
- JWT Authentication  


# Tools & Environment
- Visual Studio Code  
- Postman (API Testing)  
- Git & GitHub


# Folder Structure
FullStack_Ecommerce_App/
│
├── backend/ # Express API and MongoDB models
├── frontend/ # React UI components and pages
├── .env.example # Environment variables
├── package.json # Dependencies
└── README.md # Project documentation

# Clone the repository
```bash
git clone https://github.com/your-username/FullStack_Ecommerce_App.git

# Navigate to project folder
cd FullStack_Ecommerce_App

# Install dependencies for both frontend and backend
cd backend
npm install
cd ../frontend
npm install

# Setup environment variables

Create a .env file inside the backend folder with:

>MONGO_URI = your_mongodb_connection_string
>JWT_SECRET = your_jwt_secret_key
>PORT = 5000

# Run the development servers
>>Run backend
cd backend
npm start

>>Run frontend
cd ../frontend
npm start


# Future Enhancements

>Payment Gateway Integration (Razorpay / Stripe)

>Order Tracking System

>Cloud Image Storage (AWS S3)

>Progressive Web App (PWA) Support

# Author

Priya Rani
4th Year B.Tech — Computer Science Engineering (Data Science Minor)
📍 Lovely Professional University, Punjab
   Passionate about Full-Stack Development, Data Science, and AI-based innovation.

# License

>This project is open-source under the MIT License.
>Feel free to use, modify, and share with proper credit
