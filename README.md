# Employee Manager — Backend

This is the backend part of the Employee Manager application, built with Java and Spring Boot. It provides a RESTful API for managing employee records and is designed to work with the React frontend.

---

## Technologies Used

- Java 24
- Spring Boot
- Spring Data JPA
- PostgreSQL
- Maven

---

## Features

- REST API for employee management
- Create, read, update, delete (CRUD) operations
- Supports cross-origin requests (CORS) for frontend access
- Configurable database connection

---

## Getting Started

### Prerequisites

- Java 24
- Maven
- PostgreSQL

---

### Setup Instructions

1. Clone the repository or download the ZIP file:

```bash
git clone https://github.com/kirkosm/employee-manager-backend.git
cd employee-manager-backend
Configure the database in src/main/resources/application.properties
mvnw spring-boot:run
The backend will start on: http://localhost:8080

Base URL: http://localhost:8080/employees

Method	Endpoint	Description

GET	/employees	         Get all employees
GET	/employees/{id}   	 Get employee by ID
POST	/employees	       Create a new employee
PUT	/employees/{id}	     Update an existing employee
DELETE	/employees/{id}	 Delete an employee

Make sure the frontend is running at http://localhost:3000
