<h1> UserAuthWebApp </h1> 

A Java web application built using Servlet, JSP, MySQL, and Tomcat to handle user registration, login, profile management, and session handling.

<h3>Features</h3>

- User Registration
- Login/Logout
- Password hashing
- Session Management
- MVC Pattern

<h3>Tech Stack </h3>

- Java (Servlets + JSP)
- MySQL 8.4.4
- Apache Tomcat 10
- Eclipse IDE

<h3>Setup Instructions</h3>

1. Clone the repository:
   git clone https://github.com/arvindparaliya/UserAuthWebApp.git

2. Import the project into Eclipse as a Dynamic Web Project.

3. Update your MySQL credentials in `DbConnection.java`.

4. Create the `mvc_db` database and table: <br/>
5.```sql <br>
  CREATE DATABASE mvc_db; <br>

  USE mvc_db; <br>

  CREATE TABLE register ( <br>
    name VARCHAR(100),  <br>
    email VARCHAR(100) PRIMARY KEY, <br>
    password VARCHAR(255), <br>
    city VARCHAR(100) <br>
    );

6. Run the project on Tomcat 10.
