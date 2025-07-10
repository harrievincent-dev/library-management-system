# Library Management System

A modern library management system built with Spring Boot and React.

## 🚀 Features

- **Book Management**
  - Add, update, delete books
  - Search by title, author, ISBN
  - Category-wise organization
  - Stock tracking

- **Member Management**
  - Member registration and profiles
  - Borrowing history
  - Fine management
  - Membership types

- **Borrowing System**
  - Issue and return books
  - Due date tracking
  - Automatic fine calculation
  - Renewal options

- **Admin Features**
  - Dashboard with statistics
  - Member management
  - Book inventory control
  - Reports generation

## 🛠️ Technologies Used

**Backend:**
- Java 17
- Spring Boot 3.x
- Spring Security with JWT
- Spring Data JPA
- H2/MySQL Database
- Maven

**Frontend:**
- React 18
- Material-UI
- Axios
- React Router
- React Context API

## 📋 Prerequisites

- Java 17+
- Node.js 16+
- Maven 3.6+
- MySQL 8.0+ (optional, H2 included)

## 🔧 Installation & Setup

### Backend Setup
```bash
cd backend
mvn clean install
mvn spring-boot:run
