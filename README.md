# Green Wash - On-Demand Car Wash Service
## Live Link -- https://on-demand-car-wash-app.netlify.app/

Green Wash provides a convenient solution for getting your car washed at your preferred location. Whether you're at home, the office, or anywhere else, Green Wash brings professional car washing services right to you. Simply sign up, enter your car and address details, and a washer will come to your location to give your car a premium wash. 

## Problem Statement

**Green Wash** aims to provide an efficient and user-friendly platform where customers can book car washing services at their convenience. The application allows users to:
- Sign up and log in
- Add car and payment details
- Select and book wash packages
- Make payments through RazorPay
- View transaction history
- Receive payment receipts
- Provide reviews and ratings
- Manage their profile and order history

For car washers, the application provides:
- Login functionality
- Wash assignment by admin
- Profile management
- Viewing current and past orders

The admin panel enables:
- User management (customers and washers)
- Car management
- Service plan management
- Order management

## Features

### For Customers:
- **Sign Up/Login**: Users can register and log in using their email. Password reset functionality is available.
- **Car & Payment Details**: Users can add their car details and payment information.
- **Wash Now**: Users can book a car wash by selecting a wash package.
- **Payment**: Payments can be made using debit/credit cards through RazorPay.
- **Transaction History**: Users can view and export their transaction history.
- **Receipt**: Users receive a downloadable payment receipt after the car wash.
- **Reviews & Ratings**: Users can rate and review washers.
- **Profile**: Users can view and edit their profile information.
- **My Orders**: Users can view current, past, and cancelled orders and export order details.

### For Car Washers:
- **Login**: Washers can log in and reset their password.
- **Wash Assign**: Admin assigns washes to washers. Washers can also self-assign work.
- **Profile**: Washers can update their profile information.
- **My Orders**: Washers can view current and past orders.

### Admin Panel:
- **User Management**: Manage customers and washers, view ratings, and export reports.
- **Car Management**: Add and edit car details.
- **Service Plan Management**: Add and edit service plans.
- **Order Management**: View and assign orders, manage order status.

## Tech Stack

### Frontend
- **React**: The UI is built using React, providing a responsive and dynamic user interface.

### Backend
- **Spring Boot**: The backend services are implemented using Spring Boot, which includes an embedded Tomcat server for handling HTTP requests.
- **Databases**: Persistent data is stored using MySQL and MongoDB databases.
- **RazorPay**: Integrated for handling payments.

### Microservices
- Each microservice exposes REST/JSON endpoints for business capabilities.
- Business functions are implemented using the Spring(Boot) framework.
- Best practices such as exception handling and test cases are implemented.
- Microservices use embedded Tomcat server as the HTTP listener.

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
All microservices are accessed through the API Gateway, which acts as a single entry point to the system. The actual endpoints of the microservices are not exposed directly; instead, all communication is routed through the API Gateway on port 9002.
