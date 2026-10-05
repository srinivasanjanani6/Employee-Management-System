# Employee Management System

A Spring Boot REST API project implementing CRUD operations for **Employee and Department management** using Java, Spring Data JPA, Hibernate, and H2 Database.

## 🚀 Project Overview

The Employee Management System is a backend REST API application developed using Spring Boot. It provides APIs to manage employees and departments with complete **Create, Read, Update, and Delete (CRUD)** operations.

The project demonstrates the use of REST APIs, Spring Data JPA, Hibernate ORM, and an H2 in-memory database.

## 🛠️ Technologies Used

* **Java**
* **Spring Boot**
* **Spring Data JPA**
* **Hibernate**
* **H2 Database**
* **REST API**
* **Maven**
* **Postman** for API testing
* **IntelliJ IDEA**

## ✨ Features

### Employee Management

* Add a new employee
* Get all employees
* Get employee by ID
* Update employee details
* Delete an employee

### Department Management

* Add a new department
* Get all departments
* Get department by ID
* Update department details
* Delete a department

## 📂 Project Structure

```text
src
└── main
    ├── java
    │   └── com.example.employeemanagement
    │       ├── controller
    │       ├── entity
    │       ├── repository
    │       ├── service
    │       └── EmployeeManagementApplication.java
    │
    └── resources
        └── application.properties
```

## 🔗 REST API Endpoints

### Employee APIs

| Method | Endpoint              | Description        |
| ------ | --------------------- | ------------------ |
| POST   | `/api/employees`      | Create employee    |
| GET    | `/api/employees`      | Get all employees  |
| GET    | `/api/employees/{id}` | Get employee by ID |
| PUT    | `/api/employees/{id}` | Update employee    |
| DELETE | `/api/employees/{id}` | Delete employee    |

### Department APIs

| Method | Endpoint                | Description          |
| ------ | ----------------------- | -------------------- |
| POST   | `/api/departments`      | Create department    |
| GET    | `/api/departments`      | Get all departments  |
| GET    | `/api/departments/{id}` | Get department by ID |
| PUT    | `/api/departments/{id}` | Update department    |
| DELETE | `/api/departments/{id}` | Delete department    |

## 🗄️ Database

This project uses **H2 Database** as an in-memory database.

H2 is useful for development and testing because it does not require a separate database server.

## ▶️ How to Run the Project

### 1. Clone the repository

```bash
git clone <your-github-repository-url>
```

### 2. Open the project

Open the project in **IntelliJ IDEA** or any Java IDE.

### 3. Build the project

Using Maven:

```bash
mvn clean install
```

### 4. Run the application

Run:

```text
EmployeeManagementApplication.java
```

Or use:

```bash
mvn spring-boot:run
```

### 5. Test the APIs

Use **Postman** to test the REST API endpoints.

The application will normally run at:

```text
http://localhost:8080
```

## 🧪 API Testing

The APIs can be tested using Postman by sending HTTP requests such as:

```text
POST
GET
PUT
DELETE
```

for Employee and Department resources.

## 🎯 Learning Objectives

This project helped me understand:

* Spring Boot application development
* REST API development
* CRUD operations
* Spring Data JPA
* Hibernate ORM
* Entity relationships
* Repository layer
* Service layer
* Controller layer
* H2 Database
* API testing using Postman

## 👩‍💻 Author

**Janani Srinivasan**

B.Tech Information Technology Graduate

---

⭐ If you find this project useful, feel free to give it a star!
