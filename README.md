# :oncoming_taxi: Taxi service application :oncoming_taxi:
----
*This is a simple web application of a taxi service, which you can use as a taxi driver.*
## :large_orange_diamond: Project description
----
### In this application you can:
- Register, log in/out as a driver;<br />
- Create and delete cars/manufacturers/drivers;<br />
- Display all manufacturers/cars/drivers;<br />
- Add a driver to one or more cars;<br />
- Display all cars belonging to the driver you are logged in for;<br />
## :large_orange_diamond: Project structure
----
##### *This project has N-tier architecture. It consists of:*
- Controller - accept http requests from users and display information.
- Service - all business-logic is located here.
- DAO - all interaction with DataBase is located here
## :large_orange_diamond: Instructions for launching the project
----
- Fork this repository
- Clone the repository to PC
- Create a database in your DBMS. The template can be taken from ***src\main\resources\init_db.sql***<br />
- Edit ***taxi.util.ConnectionUtil*** class - set needed parameters in following fields
``` java
    private static final String URL = "Set URL to database";
    private static final String USERNAME = "Set USERNAME";
    private static final String PASSWORD = "Set PASSWORD";
    private static final String JDBC_DRIVER = "Set path to the JDBC_Driver";
```
- Install Apache Tomcat.\
  *Apache Tomcat 9.0.50 you can download [here](https://archive.apache.org/dist/tomcat/tomcat-9/v9.0.50/bin/)*
- Configure the Tomcat server in your IDEA and Run the project.<br />
## :large_orange_diamond: Used technologies
----
- Java 11
- JDBC
- JSP
- Java Servlet API
- MySQL 8.0.29
- Apache Maven 3.8.1
- Apache Tomcat 9.0.50

