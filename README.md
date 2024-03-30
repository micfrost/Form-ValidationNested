# Spring Boot Security with Bcrypt and Thymeleaf

## Project Overview
This project demonstrates a Spring Boot application that uses Spring Security with Bcrypt for authentication and authorization. The application serves different web pages based on user roles and utilizes Thymeleaf for dynamic web content rendering.

## Key Features
- **User Authentication**: Secure login functionality with Bcrypt password encoding.
- **Role-Based Authorization**: Distinct access controls for different user roles (HR, Supervisor, Admin).
- **Thymeleaf Integration**: Utilizes Thymeleaf for server-side rendering of HTML content.
- **Custom Error Handling**: Implements custom error pages for unauthorized access attempts.

## Java and Spring Boot Features
- **Spring Security**: Configures user authentication and authorization for the web application.
- **JDBC User Details Manager**: Manages user details with a JDBC-backed data source.
- **Spring MVC**: Uses Model-View-Controller architecture for web application design.
- **Exception Handling in Spring**: Manages application exceptions and custom error responses.
- **Database Integration**: Configures a MySQL database for storing user details and roles.
- **Thymeleaf Security Extras**: Implements Thymeleaf's integration with Spring Security for conditional content rendering based on user roles.

## How to Run
1. Ensure MySQL is set up and running.
2. Update the `application.properties` file with your database credentials.
3. Clone the repository.
4. Run `SecurityBcrptApplication` to start the application.
5. Access the application at `http://localhost:8080`.

## Usage
- Navigate to `http://localhost:8080/login` to access the login page.
- Based on the role (HR, Supervisor, Admin), different pages and functionalities will be accessible.
- Unauthorized access attempts will be redirected to a custom error page.


## Author
Created by: Michal Frost

Happy coding.