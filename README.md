# Medicare Management System

A full-stack **healthcare management web application** built using
**Angular** (frontend) and **Spring Boot** (backend).\
The system enables users to manage medical services, authentication, and
online payments through a secure and scalable architecture.

------------------------------------------------------------------------

## 🚀 Features

-   User registration and login with JWT authentication\
-   Secure REST APIs using Spring Boot & Spring Security\
-   Healthcare service management\
-   Online payment integration\
-   Responsive Angular UI\
-   MySQL database integration\
-   Clean layered architecture (Controller → Service → Repository)

------------------------------------------------------------------------

## 🧱 Tech Stack

### Frontend

-   Angular\
-   TypeScript\
-   HTML / CSS\
-   Angular Material\
-   RxJS

### Backend

-   Java 8\
-   Spring Boot\
-   Spring Security\
-   Spring Data JPA\
-   JWT Authentication\
-   Maven

### Database

-   MySQL

### Payments

-   Razorpay integration

------------------------------------------------------------------------

## 📁 Project Structure

    medicare-project/
    │
    ├── frontend/                # Angular application
    │   ├── src/
    │   ├── angular.json
    │   └── package.json
    │
    ├── backend/                 # Spring Boot application
    │   ├── src/main/java/
    │   ├── src/main/resources/
    │   └── pom.xml
    │
    └── README.md

------------------------------------------------------------------------

## ⚙️ Setup Instructions

### 1️⃣ Clone the repository

``` bash
git clone https://github.com/YOUR_USERNAME/medicare-project.git
cd medicare-project
```

------------------------------------------------------------------------

### 2️⃣ Run Backend (Spring Boot)

``` bash
cd backend
mvn clean install
mvn spring-boot:run
```

Backend will start at:

    http://localhost:8080

------------------------------------------------------------------------

### 3️⃣ Run Frontend (Angular)

``` bash
cd frontend
npm install
ng serve
```

Frontend will start at:

    http://localhost:4200

------------------------------------------------------------------------

## 🗄️ Database Configuration

Update **application.properties** in:

    backend/src/main/resources/application.properties

Example:

    spring.datasource.url=jdbc:mysql://localhost:3306/medicare
    spring.datasource.username=YOUR_DB_USERNAME
    spring.datasource.password=YOUR_DB_PASSWORD
    spring.jpa.hibernate.ddl-auto=update

------------------------------------------------------------------------

## 🌍 Deployment

-   Frontend can be deployed on Netlify, Vercel, or GitHub Pages\
-   Backend can be deployed on Render, Railway, or cloud platforms\
-   Configure environment variables for database and JWT secrets before
    production deployment
