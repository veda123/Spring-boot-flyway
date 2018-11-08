# Spring-boot-flyway

Steps to Setup the Spring Boot Back end app 

1) Clone the application

  git clone https://github.com/veda123/Spring-boot-flyway.git

2) Create MySQL database

  create database test_set_tool_db.
  
3) Change MySQL username and password as per your MySQL installation

  open src/main/resources/application.properties file.

  change spring.datasource.username and spring.datasource.password properties as per your mysql installation

4) Run the app

You can run the spring boot app by typing the following command -

  mvn spring-boot:run
