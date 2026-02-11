# FitnessTrackingApplication
A RESTful Fitness Tracker API built using Spring Boot, Spring Security (JWT), MySQL, and Docker.
The application allows users to securely authenticate and track fitness activities.

 Features
JWT-based authentication
Role-based authorization (USER / ADMIN)
Activity tracking APIs
MySQL database integration
Docker support

Tech Stack
Java
Spring Boot
Spring Security
JWT
MySQL
Docker

 Authentication
All protected APIs require a JWT token in the header:
Authorization: Bearer <token>

⚙️ Environment Variables
DB_URL=jdbc:mysql://localhost:3306/fitness_demo
DB_USERNAME=root
DB_PASSWORD=your_password
JWT_SECRET=your_secret_key
