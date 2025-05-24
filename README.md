# UserAuthWebApp

A Java web application built using Servlet, JSP, MySQL, and Tomcat to handle user registration, login, profile management, and session handling.

---

## Features
- User Registration  
- Login / Logout  
- Password Hashing  
- Session Management  
- MVC Pattern

---

## Tech Stack
- Java (Servlets + JSP)  
- MySQL 8.4.4  
- Apache Tomcat 10  
- Eclipse IDE

---

## Setup Instructions

1. Clone the repository:  
   `git clone https://github.com/arvindparaliya/UserAuthWebApp.git`

2. Import the project into Eclipse as a **Dynamic Web Project**.

3. Update your MySQL credentials in `DbConnection.java`.

4. Create the database and table by running the following SQL commands in your MySQL client:

<pre>   ```sql
   CREATE DATABASE mvc_db;

   USE mvc_db;

   CREATE TABLE register (
     name VARCHAR(100),
     email VARCHAR(100) PRIMARY KEY,
     password VARCHAR(255),
     city VARCHAR(100)
   );
   </pre>
   
5. Run the project on Apache Tomcat 10.

   

