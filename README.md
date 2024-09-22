# REST API with Spring Boot, Mysql, JPA.

## Setup

1. Clone the application
  ``` 
https://github.com/givanthak/spring-boot-rest-api-tutorial.git
 ```

2. Create Mysql-database

  ```    
create database user_database

  ```

3. Change  username and password in Mysql

*open ,src/main/resources/application.properties,

*change ,spring.datasource.username, and ,spring.datasource.password, as per your mysql installation

4. Build and run the app using maven

mvn package
java -jar target/spring-boot-rest-api-tutorial-0.0.1-SNAPSHOT.jar
Alternatively, you can run the app without packaging it using -

mvn spring-boot:run
The app will start running at http://localhost:8080.

Explore Rest APIs
The app defines following CRUD APIs.

GET /api/v1/users

POST /api/v1/users

GET /api/v1/users/{userId}

PUT /api/v1/users/{userId}

DELETE /api/v1/users/{userId}
