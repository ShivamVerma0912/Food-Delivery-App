# Food Delivery Platform API

![Food Delivery Platform]

This repository contains the source code for a comprehensive food delivery platform API. The API facilitates seamless ordering of delectable food items from a wide array of restaurants. Developed using the robust Spring Boot framework, this API is empowered by MySQL as the reliable database management system. Its key features include user authentication, smooth CRUD operations for food items, and efficient order tracking.

## Key Features

- User authentication using the "MD-5" algorithm.
- Implemented CRUD operations with robust data validation.
- Seamless integration with MySQL for efficient database management.
- Utilization of Swagger for streamlined API documentation.
- Well-organized table relationships for enhanced data organization.

## Tech Stack

- Spring Boot
- Hibernate
- MySQL
- Object-Oriented Programming (OOPs)
- Postman
- Swagger
- Java

## Prerequisites

Make sure you have the following installed:

- MySQL
- Spring Boot
- Java

## Data Flow

The application architecture follows a clear data flow across four distinct layers:

1. **DTO (Data Transfer Object)**: This layer comprises classes responsible for transferring data between different parts of the application.
2. **Controller**: The controller layer handles HTTP requests, translates JSON parameters to objects, and ensures request authentication. It acts as the frontend part of the application.
3. **Service**: The business logic resides in this layer. It consists of service classes that utilize data access layer services.
4. **Repository**: This layer handles CRUD operations on the MySQL database.

## API Documentation

The API endpoints are well-documented using Swagger. The documentation is accessible at [Link to Swagger Documentation](swagger_documentation_link).

## Database Design

The API relies on a MySQL database to store and manage its data efficiently. The database design encompasses the following tables:

1. **user**: Stores user information, including usernames, passwords, and order history.
2. **food_item**: Contains comprehensive details about food items, including their names, descriptions, and prices.

## Contributors

- Shivam Verma

## Project Summary

The Food Delivery Platform API, powered by Spring Boot, presents an impressive solution for users to order food items from various restaurants seamlessly. With its robust authentication mechanism, it ensures the security of user data. Administrators can easily manage food items using the provided CRUD operations. The API efficiently communicates with the MySQL database, ensuring smooth storage and retrieval of user and food item data. Bon appétit!# Food-Delivery-App
