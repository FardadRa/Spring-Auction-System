# 🛒 Auction Management System

A full-stack auction platform built with **Java**, **Spring Boot**, **Spring Security**, **PostgreSQL**, and **REST APIs**. The application enables users to securely register, browse auction listings, participate in both **Forward** and **Dutch Auctions**, place bids, complete purchases, and manage auction activity through a responsive web interface.

---

# 📖 Overview

This project demonstrates the design and development of a complete auction platform using modern backend architecture, secure authentication, RESTful APIs, and relational database integration.

The system follows a layered Spring Boot architecture and provides secure user authentication, auction management, bidding workflows, payment processing, and persistent data storage.

---

# 👨‍💻 My Contributions

This project was independently designed and developed from scratch.

My responsibilities included:

- Designing the complete application architecture
- Building the Spring Boot backend
- Developing REST APIs for users, auctions, bidding, and payments
- Implementing Spring Security authentication and authorization
- Designing and implementing the PostgreSQL database schema
- Building both Forward Auction and Dutch Auction workflows
- Implementing bid validation and payment processing logic
- Developing the frontend using HTML, CSS, and JavaScript
- Connecting the frontend with backend REST APIs
- Configuring Maven dependencies and project structure
- Testing application functionality and debugging integration issues

---

# ✨ Features

## 🔐 Authentication

- User registration
- Secure login
- Password authentication
- Spring Security authorization
- Session management

---

## 🛍 Auction Management

- Create auction listings
- Browse auction items
- Search available auctions
- Seller item management
- Auction status tracking

---

## 💰 Bidding System

### Forward Auctions

- Place competitive bids
- Automatic highest bid tracking
- Bid validation
- Winner determination

### Dutch Auctions

- Dynamic price reduction
- Purchase at current auction price
- Automatic auction completion

---

## 💳 Payment Processing

- Purchase workflow
- Transaction handling
- Payment confirmation
- Order completion

---

## 🗄 Database

- PostgreSQL integration
- User account storage
- Auction records
- Bid history
- Payment records
- Persistent application data

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

- REST APIs

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
      ├── Authentication
      ├── User Management
      ├── Auctions
      ├── Bidding
      ├── Payments
      └── Search
                     │
                     ▼
                PostgreSQL
```

---

# 📂 Project Structure

```text
src/
├── controller/
├── service/
├── repository/
├── entity/
├── security/
├── config/
├── resources/
└── application/

pom.xml
README.md
```

---

# 🚀 Getting Started

## Prerequisites

- Java 17+
- Maven
- PostgreSQL

---

## Clone the Repository

```bash
git clone https://github.com/FardadRa/Auction-Management-System.git
cd Auction-Management-System
```

---

## Install Dependencies

```bash
mvn clean install
```

---

## Configure the Database

Update the PostgreSQL connection settings inside:

```text
src/main/resources/application.properties
```

---

## Run the Application

```bash
mvn spring-boot:run
```

The application will start locally on:

```
http://localhost:8080
```

---

# 📋 Skills Demonstrated

- Java Backend Development
- Spring Boot
- Spring Security
- REST API Development
- Object-Oriented Programming
- PostgreSQL Database Design
- Spring Data JPA
- Authentication & Authorization
- MVC Architecture
- Backend–Frontend Integration
- Full-Stack Development
- Software Architecture
- Database Modeling
- Maven Build Management
- Debugging & Testing

---

# 🔮 Future Improvements

- JWT authentication
- Docker deployment
- Admin dashboard
- Image upload support
- Email notifications
- Live bidding using WebSockets
- Payment gateway integration
- Auction analytics dashboard

---

# 📦 Release

**Current Version:** **v1.0.0**

---

# 📄 License

This project was developed for educational and portfolio purposes.
