# POS System - MERN Stack

This project is a Point of Sale (POS) system developed using the MERN stack (MongoDB, Express.js, React.js, Node.js). The application features user registration, login, customer management, order management, product management, and an income chart.

## Features

### User Registration
- Users can register for the platform by providing a unique username, email address, and password.
- The backend API validates the input, ensuring the username and email are unique, and the password meets security criteria.
- User data, including their username, email (encrypted password), and profile information, is securely stored in a database.

### User Login
- Registered users can log in by entering their username, email, and password.
- The backend API verifies the credentials against the stored data, checking if the password is correct.
- If the credentials are valid, the API generates an access token and returns it to the front end.

### Customer Management
- Manage customer information including adding, updating, and deleting customer details.

### Order Management
- Handle order creation, updating, and tracking.
- View order history and details.

### Product Management
- Manage products including adding, updating, and deleting product details.
- Track product inventory.

### Income Chart
- View graphical representations of income over time.
- Analyze sales data and performance metrics.

## Project Structure

### Backend (API)
The backend of this POS system is built using Node.js, Express.js, and MongoDB. The API handles user authentication, customer management, order management, product management, and income chart data.

GitHub Repository: [Backend API](https://github.com/Faslanrizni/pos-api)

### Frontend (Client)
The front end of the POS system is built using React.js. It interacts with the backend API to provide a seamless user experience for managing customers, orders, products, and viewing income charts.

GitHub Repository: [Frontend Client](https://github.com/Faslanrizni/react-pos-front)

## Getting Started

### Prerequisites
- Node.js
- MongoDB
- npm or yarn

### Contact me
- mail: faslan2002rizni@gmail.com
- phone: +94762720321
