# RideBuff: Car Wash Services Made Easy

**Experience RideBuff Live**: [RideBuff](https://ridebuff-car-wash.netlify.app/)

---

## Overview

**RideBuff** is your go-to solution for convenient, on-the-spot car washing services. Whether you're at home, at work, or anywhere in between, simply book a professional car wash with just a few taps. Designed for ease of use, the app allows users to schedule, manage, and track their washes effortlessly. With secure payment options and comprehensive order management, keeping your car spotless has never been simpler.

---

## The Problem We Solve

RideBuff was created to take the hassle out of keeping your car clean. No more long waits or trips to the car wash. With **RideBuff**, you get:

### For Customers:
- **Seamless Account Management**: Easily sign up, log in, and recover passwords through email.
- **Vehicle & Payment Setup**: Quickly add and manage car details and payment methods.
- **Effortless Booking**: Select your desired car wash package and schedule a service with ease.
- **Secure Payments**: Process transactions safely via **RazorPay**.
- **Complete Transaction History**: Review and export all transaction records.
- **Receipts on Demand**: Instantly download payment receipts.
- **Ratings & Reviews**: Share your experience by rating and reviewing the service.
- **Personalized Profile Management**: Update your account details whenever you need.
- **Order History**: Track all your bookings—current, past, and even canceled orders.

### For Car Washers:
- **User-Friendly Login**: Easily log in and reset passwords.
- **Job Management**: View assigned washes or choose available jobs on your own.
- **Profile Customization**: Keep your details up to date.
- **Efficient Order Management**: Review both current and completed orders seamlessly.

### For Admins:
- **Manage Users**: Oversee customers and washers, monitor ratings, and export data for analysis.
- **Service Plan Management**: Create, update, and fine-tune service packages.
- **Car Database**: Maintain up-to-date car details for accurate bookings.
- **Order Control**: Assign, manage, and track all car wash orders.

---

## Tech Stack

### Frontend:
- **React**: Delivers a smooth, responsive, and intuitive user interface.

### Backend:
- **Spring Boot**: Ensures a stable and efficient backend.
- **Spring Security**: Keeps user authentication and authorization secure.
- **JWT (JSON Web Token)**: Provides a safe, stateless way to manage user sessions.
- **Spring Cloud Gateway**: Manages API routing and security.
- **Spring MVC**: Supports scalable RESTful web services.
- **Java**: Powers the entire backend with high performance.
- **Microservices Architecture**: Offers flexibility and scalability, ensuring each service is independent.
- **MySQL & MongoDB**: Robust databases for data persistence.
- **RazorPay**: Seamlessly integrates for secure payment transactions.

---

## Microservices Overview

| Service                      | Port  |
| ----------------------------- | ----- |
| **Admin Service**             | 8081  |
| **Authentication & JWT**      | 8086  |
| **Email Notifications**       | 8088  |
| **Order Processing**          | 8082  |
| **User Data Management**      | 8083  |
| **Car Washer Operations**     | 8085  |
| **Profile Management**        | 8087  |
| **Payments**                  | 8084  |
| **API Gateway**               | 9002  |
| **Service Discovery (Eureka)**| 8761  |

---

## Central API Gateway

The **API Gateway** (Port 9002) securely routes all service requests, providing a unified, secure entry point for the entire system.

---

## Deployment

Both the backend and frontend code are securely stored to maintain data integrity, ensuring a safe and reliable user experience. Check out the live demo [here](https://ridebuff-car-wash.netlify.app/).

---
