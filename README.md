You can access the live version of this project at:

[Website URL](https://bookstore-w2kn.onrender.com/)

This project is built using Java as the backend, powered by Spring Boot for API handling and server-side processing. The backend integrates with a H2 database.

Users can browse, search and purchase books online while admin have access to check and manage orders.


🚀 Tech Stack
Java (Backend),

Spring Boot (Framework),

Spring MVC,

Spring Data JPA,

H2 Database

MySQL (Database)

Maven (Build Tool),

Thymeleaf etc.

*For accessing Admin Access:

user : admin

password : admin


Prerequisites
Make sure you have the following installed on your machine:

Java JDK (version 8 or higher)
Maven (for dependency management)
Git (for cloning the repository)


🚀 Steps to Clone and Run the Application
------------------------------------------------------------------------------------------------------------------------------
*Clone the repository: 
Open your terminal and run the following command to clone the repository:

git clone 

*Configure the database:

For development, the application uses H2 in-memory database, so no setup is required.

*Update the database connection properties in the src/main/resources/application.properties file:


spring.datasource.url=jdbc:mysql://localhost:3306/your-database

spring.datasource.username=your-username

spring.datasource.password=your-password


*Build and run the application:

Use Maven to build the project:

mvn clean install

Run the application using Maven:

mvn spring-boot:run


Access the application: Once the application is running, you can access it in your browser at:
http://localhost:8080

