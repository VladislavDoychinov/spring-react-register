Full-Stack Auth Application

A simple full-stack authentication app with a Java/Spring Boot backend and a React/TypeScript frontend. Users can register and log in securely, with data stored in MariaDB or an in-memory H2 database.

Features
User registration and login
Secure password hashing with BCrypt
Backend: Java + Spring Boot + Spring Data JPA
Frontend: React + TypeScript + Fetch API
Getting Started
Backend

Go to the backend folder:

cd backend
Configure your database in application.properties (H2).

Run the backend:

./mvnw spring-boot:run
Frontend

Go to the frontend folder:

cd frontend

Install dependencies:

npm install

Start the frontend:

npm start

Open your browser at http://localhost:3000 to use the app.

License

MIT License
