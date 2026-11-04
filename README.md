# Login and Registration System

A Java-based web application that allows users to register, log in, and log out. The project uses Java Servlets and the DAO (Data Access Object) pattern to organize authentication and database operations.

## Features

- User registration
- User login and authentication
- User logout
- Database operations using DAO classes
- Organized Java code using separate model, DAO, and servlet classes

## Technologies Used

- Java
- Java Servlets
- JDBC
- MySQL (if configured in the project)
- HTML and CSS (for the user interface)
- Apache Tomcat
- Eclipse IDE

## Project Structure

```text
LoginRegistration/
├── User.java
├── UserDao.java
├── UserDaoImpl.java
├── LoginServlet.java
├── LogoutServlet.java
├── RegisterServlet.java
├── DBUtil.java
├── .classpath
└── .project
```

*Note: The structure above lists the main files. Keep Java files in their original packages and folders when uploading the complete project.*

## How to Run

1. Install the JDK and Eclipse IDE.
2. Configure Apache Tomcat in Eclipse.
3. Configure the database connection in `DBUtil.java`.
4. Create the required database and user table according to the SQL queries in the project.
5. Add the required JDBC driver and servlet dependencies.
6. Import the project into Eclipse.
7. Run the application on Tomcat and open it in your browser.

## Learning Outcomes

- Understanding Java Servlet-based web applications
- Implementing login and registration functionality
- Learning the DAO design pattern
- Connecting Java applications to a database using JDBC
- Managing login and logout requests

## Future Improvements

- Add password hashing for secure storage
- Implement input validation
- Improve session management and authentication security
- Create a responsive user interface
- Display meaningful error and success messages

## Author

Shradha Gupta
