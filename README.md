# Product Inventory Management
### Advanced version of this app here(includes Autherization): https://github.com/rahul-siddhu/todo-list

A simple To-Do List application built with Spring Boot, Thymeleaf. This application allows users to create, read, update, and delete tasks in their to-do list.

## Features

- **CRUD Operations**: Users can create, read, update, and delete tasks.
- **Thymeleaf Templating**: Frontend views are rendered using Thymeleaf templates.

## Technologies Used

- **Spring Boot**: Framework for creating standalone, production-grade Spring-based applications.
- **Thymeleaf**: Modern server-side Java template engine for web and standalone environments.
- **Spring Data JPA**: Simplifies data access and persistence using the Java Persistence API.
- **Hibernate**: Object-relational mapping tool for the Java programming language.
- **MySQL/PostgreSQL/H2 Database**: Choose your preferred relational database for storage.

## Getting Started

### Prerequisites

- Java JDK (8 or higher)
- Maven
- Your preferred IDE (IntelliJ IDEA, Eclipse, etc.)
- MySQL/PostgreSQL/H2 Database (Make sure you have it installed and running)

### Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/rahul-siddhu/product-inventory
   ```

2. Update `application.properties` with your database configuration:

   ```properties
   spring.datasource.url=jdbc:mysql://localhost:3306/db_todolist
   spring.datasource.username={Your username}
   spring.datasource.password={Yours password}
   ```
   You need to create database with name 'product_inventory' in MySQL and also the tables needed(Model folder inside src folder haas the information regarding what tables to be created)

3. Run the application by running the file ProductInventoryApplication.java in the src folder

4. Open your browser and visit `http://localhost:8080` to access the application.

## Usage

1. **Manage Tasks**: Add, edit, delete tasks from your to-do list.


