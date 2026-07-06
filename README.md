
# E-Commerce Mini Project

## Project Overview

The E-Commerce Mini Project is a full-stack web application that simulates a real-world online shopping platform. It is designed using modern web technologies and follows industry-standard practices such as RESTful APIs, modular architecture, secure authentication, and payment gateway integration.

The application provides a complete flow starting from product browsing and cart management to order placement and admin-side product control. This project is suitable for academic submission, portfolio demonstration, and technical interviews.

---

## Features

### User Features

* User authentication (Login and Registration)
* Browse products and collections
* Product search and filtering
* Add to cart and manage cart items
* Secure checkout process
* Online payment using Stripe and Razorpay
* Order placement and order history
* Order verification and status tracking
* Chatbot support for basic user assistance

### Admin Features

* Admin authentication
* Add, update, and delete products
* View all customer orders
* Manage order status
* Product listing dashboard

---

## Technology Stack

### Frontend

* React.js (Vite)
* Tailwind CSS
* JavaScript (ES6+)
* Context API for state management

### Backend

* Node.js
* Express.js
* RESTful APIs
* Middleware for authentication and validation

### Database

* MongoDB
* Mongoose ODM

### Payment Gateways

* Stripe
* Razorpay

### Tools and Platforms

* Git and GitHub
* Vercel (Deployment)
* Postman (API testing)

---

## Project Architecture

The project follows a modular MERN stack architecture:

* Frontend handles UI, routing, and state management
* Backend handles business logic and API endpoints
* MongoDB stores users, products, orders, and payments
* Admin and user applications are separated for better role management

---

## Folder Structure

```
E-Commerce-Mini-Project/
│
├── admin/                  # Admin dashboard
│   ├── components/
│   ├── pages/
│   ├── App.jsx
│   └── main.jsx
│
├── backend/                # Backend APIs
│   ├── config/             # Database & environment configuration
│   ├── controllers/        # Business logic
│   ├── middleware/         # Authentication & validation
│   ├── models/             # Database schemas
│   ├── routes/             # API routes
│   └── server.js           # Server entry point
│
├── frontend/               # User-facing frontend
│   ├── components/
│   ├── context/
│   ├── pages/
│   ├── App.jsx
│   └── main.jsx
│
├── .env                    # Environment variables
├── package.json
├── vercel.json
└── README.md
```

---

## Environment Variables

Create a `.env` file in the backend directory and add the following:

```
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
STRIPE_SECRET_KEY=your_stripe_secret_key
RAZORPAY_KEY_ID=your_razorpay_key
RAZORPAY_KEY_SECRET=your_razorpay_secret
```

---

## Installation and Setup

### Prerequisites

* Node.js installed
* MongoDB database
* Git installed

### Backend Setup

```
cd backend
npm install
npm start
```

### Frontend Setup

```
cd frontend
npm install
npm run dev
```

### Admin Panel Setup

```
cd admin
npm install
npm run dev
```

---

## API Flow Overview

* User authentication APIs handle login and registration
* Product APIs fetch, add, update, and delete products
* Cart APIs manage cart operations
* Order APIs manage checkout and order history
* Payment APIs handle Stripe and Razorpay transactions
* Admin APIs control product and order management

---

## Deployment

* Frontend deployed using Vercel
* Backend configured for production deployment
* Environment variables securely managed on deployment platform

---

## Security Practices

* Sensitive data stored using environment variables
* JWT-based authentication
* Middleware for route protection
* Secure payment handling via trusted gateways

---

## Learning Outcomes

* Full-stack MERN application development
* REST API design and integration
* Database schema design using MongoDB
* Payment gateway integration
* Role-based access (User and Admin)
* Real-world project structuring and deployment

---

## Future Enhancements

* Role-based access control for admins
* Product reviews and ratings
* Wishlist functionality
* Email notifications
* Improved chatbot intelligence
* Performance optimization and caching

---

## Contribution Guidelines

1. Fork the repository
2. Create a new feature branch
3. Commit changes with meaningful messages
4. Push the branch and create a pull request

---

## License

This project is created for educational and demonstration purposes.

---


