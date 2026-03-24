# Full-Stack Auth Application

A simple full-stack authentication app with a Java/Spring Boot backend and a React/TypeScript frontend. Users can register and log in securely, with data stored in H2.

---

## Features
- User registration and login
- Secure password hashing with BCrypt
- Backend: Java, Spring Boot, Spring Data JPA
- Frontend: React, TypeScript, Fetch API

---

## Run the Project

### Backend
```bash
cd backend
./mvnw spring-boot:run
```

### Frontend
```bash
cd frontend
npm install
npm start
```
### Access to the H2 Database
```bash
http://localhost:8080/h2-console
```
### To log in for the database:
JDBC URL:
```bash
 jdbc:h2:mem:testdb
```
User:
```bash
 sa
```
The password is just empty field.
