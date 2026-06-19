# Employee Management System

A full-stack Employee Management System built using ReactJS, Spring Boot, Hibernate, and MySQL.

## Features

- Add Employee
- View Employee Details
- Update Employee Information
- Delete Employee
- REST API Integration
- Responsive User Interface
- MySQL Database Connectivity

## Tech Stack

### Frontend
- ReactJS
- Bootstrap
- Axios
- React Router

### Backend
- Spring Boot
- Spring Data JPA
- Hibernate
- Maven

### Database
- MySQL

## Installation

### Backend Setup

```sql
CREATE DATABASE employee_management_system;
```

Configure MySQL in:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/employee_management_system
spring.datasource.username=root
spring.datasource.password=your_password
spring.jpa.hibernate.ddl-auto=update
```

Run backend:

```bash
mvn spring-boot:run
```

### Frontend Setup

```bash
cd react-frontend
npm install
npm start
```

## API Endpoints

| Method | Endpoint | Description |
|---------|----------|-------------|
| GET | /api/v1/employees | Get All Employees |
| GET | /api/v1/employees/{id} | Get Employee By ID |
| POST | /api/v1/employees | Add Employee |
| PUT | /api/v1/employees/{id} | Update Employee |
| DELETE | /api/v1/employees/{id} | Delete Employee |

## Project Structure

```text
employee-management-system
│
├── react-frontend
├── springboot-backend
└── README.md
```

## Author

**PAVITHRA**

GitHub: https://github.com/23211a6699

## License

This project is created for educational and learning purposes.
