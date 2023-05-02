# Taxi-Service

`A simple web-application that supports authentication, registration and other CRUD operations. 
Project works on SQL and TomCat 9.0.74`
___

## Features

+ registration like a driver;
+ authentication like a driver;
+ create/update/remove a manufacturers;
+ create/update/remove a car;
+ create/update/remove driver;
+ display list of all manufacturers;
---
## How to launch

1. You should prepare Tomcat 9.0.74.
2. In Tomcat Deployment change Application context to "/ "
3. Use File `src/main/resources/init_db.sql` to create new DB.
4. In class ConnectionUtil `src/main/java/taxi/util/ConnectionUtil.java` make connection with you DB.
You should replace `URL`, `USERNAME`, `PASSWORD`, `JDBC_DRIVER` with your properties.
5. Build project by using Maven.
6. Use Tomcat to launch application.
---
## Structure
+ Controller: Servlets that handle HTTP requests and responses.
+ Dao:  Data Access Object interfaces and their implementations.
+ Exception: Custom exception that will be thrown in web application.
+ Lib: Custom Injector and annotations that will be used for object initialization.
+ Service: Service contains all business logic.
+ Util: Makes connection with your DB and used in DAO.
+ Filer: Filer for making authentication in web application.
+ Resources: Contains scripts for creating your DB.
+ WEB-INF: Contains file configurations for Servlets.
+ Views: Contains all JSP pages and CSS file.
---
## Used Technologies

+ Java `v.19.0.1`
+ Maven `v.3.8.6`
+ JDBC `v.4.2`
+ MySql `v.8.0.22`
+ Javax Servlets `v.4.0.1`
+ JSTL `v.1.2`
+ Tomcat `v.9.0.74`