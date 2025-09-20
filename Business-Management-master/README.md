# Business Management Web Application : <br>

https://github.com/Durgarao13/Business-Management

# 🏢 Business Management Project

A full-stack **Spring Boot + MySQL** web application designed for managing business operations efficiently.  
This project demonstrates enterprise-level backend development with database integration and REST endpoints.


## Features  :

- **Customer Management**: Easily add, update, and delete customer information.
- **Inventory Management**: Keep track of your inventory items, including stock levels and pricing.
- **Order Management**: Manage customer orders such as order creation .
- **User Authentication**: Secure login and authentication for admin and staff members.
- **Role-Based Access Control**: Define roles and permissions for different user types.
- **Thymeleaf Templates**: Utilizes Thymeleaf for dynamic HTML templates.
- **Database Integration**: Integrated with MySQL for data storage.




## Technologies Used :

- Spring Boot: Backend framework for building Java-based web applications.
- Thymeleaf: Server-side Java template engine for dynamic HTML generation.
- MySQL: Relational database management system for data storage.
- IDE/Tool : Spring Tool Suite 4 (Eclipse)




## Installation :

### 1. Clone the repository
```bash
git clone https://github.com/Durgarao13/Business-Management.git
cd Business-Management
2. Configure the Database

Login to MySQL and create the DB:

CREATE DATABASE businessproject CHARACTER SET utf8mb4 COLLATE utf8mb4_unicode_ci;


Check/edit src/main/resources/application.properties:

spring.datasource.url=jdbc:mysql://localhost:3306/businessproject?useSSL=false&serverTimezone=UTC
spring.datasource.username=root
spring.datasource.password=your_password
spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver
spring.jpa.hibernate.ddl-auto=update
server.port=2330

3. Build & Run

Run with Maven:

mvn spring-boot:run


Or package into a JAR:

mvn clean package
java -jar target/BusinessProject-0.0.1-SNAPSHOT.jar

🌐 Access the App

Once running, open in browser:

Home: http://localhost:2330/home

About Us: http://localhost:2330/about

📦 Deployment Notes

Build artifacts (target/) are ignored in Git to keep the repo clean.

To distribute, build the JAR locally and upload via GitHub Releases.

🧑‍💻 Author

Durga Rao Geddam

💼 IT Intern at University IDD Ed Center

📚 Passionate about full-stack development
    








## Preview :

https://github.com/Durgarao13/Business-Management


![exceptionPage](https://github.com/SuhasKamate/Business_Management_Project/assets/126138738/4349a429-61ff-4ecd-a463-2900874e1ea5)
