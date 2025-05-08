# Inventory Management System

A Spring Boot application for managing inventory items using a MySQL database. Supports full CRUD operations via RESTful API.

---

## Features

- Add, view, update, and delete items
- RESTful API endpoints
- MySQL database integration
- Exception handling for clean error responses
- Tested via Postman

---

## Tech Stack

- Java 19
- Spring Boot 3.4.4
- Spring Web
- Spring Data JPA
- MySQL
- Maven

---

## Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/kashishdesai03/inventory-management-system.git
cd inventory-management-system
```

### 2. MySQL Setup
- Open MySQL Workbench or terminal
- Run the following to create the database:
```sql
CREATE DATABASE inventorydb;
```

### 3. Configure Application
```markdown
### 3. Configure Application
Update `src/main/resources/application.properties`:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/inventorydb
spring.datasource.username=your_mysql_username
spring.datasource.password=your_mysql_password
spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
```

### 4. Run the Application
```markdown
### 4. Run the Application
In IntelliJ:
- Open `InventoryApplication.java`
- Click the green ▶️ to run the app

It will start at:
http://localhost:8080
```
