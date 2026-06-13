# Student Management System

## Overview

Student Management System is a Full Stack CRUD application developed using Spring Boot, MySQL, REST APIs, and Postman.

The application allows users to:

- Add Students
- View Students
- Update Student Details
- Delete Students

## Technologies Used

- Java
- Spring Boot
- MySQL
- Spring Data JPA
- REST API
- Postman
- Maven

## Architecture

Frontend → REST API → Spring Boot → MySQL

## API Endpoints

### Get All Students

GET

```
/api/students
```

### Get Student By ID

GET

```
/api/students/{id}
```

### Create Student

POST

```
/api/students
```

### Update Student

PUT

```
/api/students/{id}
```

### Delete Student

DELETE

```
/api/students/{id}
```

## Database Schema

```sql
CREATE TABLE students(
id BIGINT PRIMARY KEY AUTO_INCREMENT,
name VARCHAR(100),
email VARCHAR(100),
course VARCHAR(100)
);
```

## Features

- CRUD Operations
- RESTful APIs
- MySQL Integration
- Postman Testing
- MVC Architecture

## Author

Karangula Jahnavi
