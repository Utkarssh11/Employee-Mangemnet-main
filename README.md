
# Employee Management System

A full-stack web application for managing employee records, built using **Spring Boot**, **MySQL**, and **JPA**. This project demonstrates core backend development concepts including CRUD operations, RESTful APIs, MVC architecture, and object-relational mapping.

---

## Tech Stack

- **Backend:** Java, Spring Boot, JPA, Hibernate
- **Database:** MySQL (also tested with PostgreSQL)
- **Tools:** Eclipse, Postman
- **Architecture:** RESTful APIs, MVC, OOP Principles

---

## Features

- Add, update, delete, and view employee records
- REST API design following standard HTTP methods
- Object-Relational Mapping using JPA and Hibernate
- MVC pattern to separate concerns
- Postman-tested endpoints for API validation

---

## Project Structure

```

employeemanagementsystem/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── edu/jspiders/studentmanagementsystem/
│   │   │       ├── controller/
│   │   │       ├── entity/
│   │   │       ├── repository/
│   │   │       └── service/
│   │   └── resources/
│   └── test/
├── target/
├── pom.xml
├── README.md
├── mvnw
├── mvnw\.cmd
└── HELP.md

```


---

## API Endpoints

| Method | Endpoint             | Description               |
|--------|----------------------|---------------------------|
| GET    | `/employees`         | Get all employees         |
| GET    | `/employees/{id}`    | Get employee by ID        |
| POST   | `/employees`         | Add new employee          |
| PUT    | `/employees/{id}`    | Update employee by ID     |
| DELETE | `/employees/{id}`    | Delete employee by ID     |

---

## Getting Started

### Prerequisites

- Java 17+
- MySQL or PostgreSQL
- Maven
- Postman (for testing)

## Setup Instructions

````markdown
## Setup Instructions

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Utkarssh11/employee-management-system.git
````

2. **Set up your MySQL/PostgreSQL database** and update the `application.properties` file:

   ```properties
   spring.datasource.url=jdbc:mysql://localhost:3306/employee_db
   spring.datasource.username=yourUsername
   spring.datasource.password=yourPassword
   spring.jpa.hibernate.ddl-auto=update
   spring.jpa.show-sql=true
   ```

3. **Build and run the project** using Maven or your IDE:

   ```bash
   mvn spring-boot:run
   ```

4. **Test the API using Postman.** Use the API endpoints (e.g., `/employees`, `/employees/{id}`) to perform CRUD operations.


