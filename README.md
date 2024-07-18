# Car Wash - A Car washing Management service app

## Live Link
Experience the app live: [Car Wash App](https://on-demand-car-wash-app.netlify.app/)

## Overview
Car Wash offers a convenient solution for scheduling on-site car washing services. Users can book a professional car wash at any location they choose, such as their home or office, with an easy sign-up process and intuitive interface.

## Problem Statement
Car Wash aims to provide a seamless and efficient platform for booking car wash services. The application includes:

### For Customers:
- **Account Management**: Register, log in, and reset passwords via email.
- **Car & Payment Details**: Add and manage car and payment information.
- **Booking**: Choose and book car wash packages.
- **Payments**: Secure transactions through RazorPay.
- **Transaction History**: Access and export transaction history.
- **Receipts**: Downloadable payment receipts.
- **Reviews & Ratings**: Submit reviews and ratings for car washers.
- **Profile Management**: Edit personal profile details.
- **Order History**: View and export current, past, and cancelled orders.

### For Car Washers:
- **Login**: Secure login and password reset.
- **Wash Assignments**: Admin-assigned or self-assigned washes.
- **Profile Management**: Update personal details.
- **Order Management**: View current and past orders.

### Admin Panel:
- **User Management**: Manage customers and washers, monitor ratings, and export reports.
- **Car Management**: Add and update car details.
- **Service Plan Management**: Create and edit service plans.
- **Order Management**: Manage and assign orders.

## Tech Stack

### Frontend
- **React**: Responsive and dynamic UI.

### Backend
- **Spring Boot**: Backend services with embedded Tomcat for HTTP requests.
- **Databases**: Persistent storage using MySQL and MongoDB.
- **RazorPay**: Integrated for secure payments.

### Microservices Architecture
- **Admin Service**: Port 8081
- **Login and Signup with JWT Security**: Port 8086
- **Email Service**: Port 8088
- **Order Service**: Port 8082
- **User Service**: Port 8083
- **Washer Service**: Port 8085
- **Profile Management Service**: Port 8087
- **Payment Service**: Port 8084
- **API Gateway**: Port 9002
- **Service Registry (Eureka)**: Port 8761

### API Gateway
All microservices are accessed through the API Gateway on port 9002, ensuring a secure and unified entry point.

---

## Note
The backend and frontend code for this application are private to ensure security and data integrity. Only the deployed application is visible to users.
