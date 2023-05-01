# Taxi-Service

`A simple web-application that supports authentication, registration and other CRUD operations`
___

## Features

+ registration like a driver;
+ authentication like a driver;
+ create/update/remove a manufacturers;
+ create/update/remove a car;
+ create/update/remove driver;
+ display list of all manufacturers;

## How to launch

1. You should prepare Tomcat 9.0.74.
2. In Tomcat Deployment change Application context to "/ "
3. Use File src/main/resources/init_db.sql to create new DB.
4. In class ConnectionUtil src/main/java/taxi/util/ConnectionUtil.java make connection with you DB.
5. Use Tomcat to launch application.