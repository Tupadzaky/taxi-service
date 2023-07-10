# Taxi-Service

### Project description:
This is a simple project that shows my Java Core, OOP, SOLID, JDBC and Java Web skills. In this project, you can find CRUD operations implementations for work with Car, Manufacturer, and Driver entities that use one-to-one, one-to-many, and many-to-many relationships.

### Application provides next functionality:
- register/login as a driver
- create/delete/update a driver
- display all drivers
- create/delete/update a car
- add a driver to a car
- display all cars
- create/delete/update a manufacturer
- display all manufacturers

### Project Structure
- Controller Layer: Provides logic for responding to users requests. Communicates with the Service Layer to access business logic.
- Service Layer: Provides business logic for the entire application. Communicates with the DAO Layer to perform operations with entities.
- DAO Layer: Provides access to CRUD operations for work with Car, Manufacurer and Driver entities.

### Technologies used: 
- Java 17
- JDBC
- Java Servlet API
- JSP
- JSTL
- Tomcat 9.0.76
- MySQL 
- Maven 

### To run the project follow next steps:
1. Clone this project from GitHub to your PC.
2. Install Apache Tomcat version 9.0.xx.
3. Install MySQL.
4. Create the necessary tables in your database from the file [init_db.sql](src/main/resources/init_db.sql).
5. Cofigure field values to your specific properties in the [ConnectionUtil](src/main/java/taxi/util/ConnectionUtil.java) class.
    - private static final String MYSQL_DRIVER = "com.mysql.cj.jdbc.Driver";
    - private static final String USERNAME = "YOUR_USERNAME";
    - private static final String PASSWORD = "YOUR_PASSWORD";
    - private static final String DB_URL = "YOUR_URL";
7. Run the project.
