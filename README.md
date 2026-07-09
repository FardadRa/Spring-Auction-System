# 🛒 Spring Auction System

A full-stack auction platform built with **Java**, **Spring Boot**, **Spring Security**, **PostgreSQL**, and **REST APIs**. The system enables users to securely register, browse auction listings, participate in both **Forward** and **Dutch Auctions**, place bids, complete purchases, and manage auction activity through a responsive web application.

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![REST API](https://img.shields.io/badge/REST_API-00599C?style=for-the-badge)

---

# 📖 Overview

Spring Auction System is a full-stack auction platform developed using Spring Boot and PostgreSQL. The application demonstrates enterprise backend development concepts including layered architecture, authentication, RESTful APIs, business logic implementation, and database integration.

Users can securely register, browse auction listings, search products, participate in both Forward and Dutch auctions, place bids, and complete purchases through a responsive web interface.

---

# 👨‍💻 My Contributions

This project was independently designed and developed from scratch.

My responsibilities included:

- Designing the complete system architecture
- Developing the Spring Boot backend
- Implementing REST APIs for users, auctions, bids, catalogue management, and authentication
- Configuring Spring Security authentication and authorization
- Designing and implementing the PostgreSQL database schema
- Building business logic for both Forward and Dutch auctions
- Implementing bid validation and auction workflows
- Developing responsive frontend pages using HTML, CSS, and JavaScript
- Connecting frontend pages with backend REST APIs
- Configuring Maven dependencies and application properties
- Testing, debugging, and integrating frontend and backend functionality

---

# ✨ Features

## 🔐 Authentication

- User registration
- Secure login
- Spring Security authentication
- Session management

---

## 🛒 Auction Management

- Create auction listings
- Browse active auctions
- Search catalogue items
- Manage auction lifecycle
- Seller item management

---

## 💰 Bidding

### Forward Auctions

- Competitive bidding
- Highest bid validation
- Winner determination

### Dutch Auctions

- Dynamic price reduction
- Buy-now functionality
- Automatic auction completion

---

## 💳 Payment

- Purchase workflow
- Transaction processing
- Order completion

---

## 🗄 Database

- PostgreSQL integration
- User management
- Auction records
- Bid history
- Catalogue storage

---

# 🛠 Tech Stack

## Backend

- Java
- Spring Boot
- Spring Security
- Spring Data JPA
- Maven

## Database

- PostgreSQL

## Frontend

- HTML
- CSS
- JavaScript

## APIs

- RESTful APIs

---

# 🏗 Architecture

```text
                  Browser
                      │
                      ▼
          HTML • CSS • JavaScript
                      │
              REST API Requests
                      │
                      ▼
             Spring Boot Backend
      ┌────────────────────────────────┐
      │ Authentication                 │
      │ User Management                │
      │ Auctions                       │
      │ Catalogue                      │
      │ Bidding                        │
      │ Payments                       │
      └────────────────────────────────┘
                      │
                      ▼
                 PostgreSQL
```

---

# 📂 Project Structure

```text
src
├── main
│   ├── java
│   │   ├── config
│   │   ├── controller
│   │   ├── model
│   │   ├── repository
│   │   ├── service
│   │   └── SpringAuctionSystemApplication.java
│   │
│   └── resources
│       ├── static
│       ├── templates
│       └── application.properties
│
└── test

pom.xml
README.md
```

---

# 📚 Key Concepts Demonstrated

- Layered Spring Boot Architecture
- MVC Design Pattern
- Object-Oriented Programming
- REST API Development
- Spring Security
- Authentication & Authorization
- Repository Pattern
- Service Layer Architecture
- CRUD Operations
- PostgreSQL Integration
- Database Design
- Backend Business Logic
- Full-Stack Web Development
- Client–Server Communication

---

# 🚀 Getting Started

## Prerequisites

- Java 17+
- Maven
- PostgreSQL

---

## Clone the Repository

```bash
git clone https://github.com/FardadRa/Spring-Auction-System.git

cd Spring-Auction-System
```

---

## Configure the Database

Update the PostgreSQL connection inside:

```
src/main/resources/application.properties
```

---

## Build the Project

```bash
mvn clean install
```

---

## Run the Application

```bash
mvn spring-boot:run
```

The application will start locally at:

```
http://localhost:8080
```

---

# 🔮 Future Improvements

- JWT authentication
- Docker deployment
- Admin dashboard
- Image upload support
- Live bidding using WebSockets
- Email notifications
- Payment gateway integration
- Auction analytics dashboard

---

# 📦 Release

**Current Version:** **v1.0.0**

---

# 📝 Notes

This project was independently developed as a software engineering project and is maintained as part of my professional software engineering portfolio.
