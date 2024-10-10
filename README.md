# Simple REST Service

## Overview
This project is a simple RESTful web service built with Spring Boot. It returns a greeting message that can be customized using a query parameter.

## Prerequisites
- Java 11 (or the version installed on your system)
- Maven
- Spring Boot 2.7.0 (or the latest stable version)

## Steps to Set Up the Project

### 1. Generate the Project
1. Go to [Spring Initializr](https://start.spring.io/).
2. Configure the project:
   - **Project**: MAVEN Project
   - **Language**: Java
   - **Spring Boot**: 2.7.0
   - **Group**: com.example
   - **Artifact**: simple-rest-service
   - **Name**: SimpleRestService
   - **Package name**: com.example.simplerestservice
   - **Packaging**: Jar
   - **Java**: 11
3. Add the dependency: **Spring Web**.
4. Click on **Generate** to download the project, then unzip it.

### 2. Import the Project
1. Open your IDE (IntelliJ IDEA, Eclipse, etc.).
2. Import the unzipped project as a Maven project.
   
### 3. Create Model and Controller Classes
1. Create a package named `model` under `src/main/java/com/example/simplerestservice`.
2. Create a Java class named **Greeting** in the `model` package.
3. Create a package named `controller` under `src/main/java/com/example/simplerestservice`.
4. Create a Java class named **GreetingController** in the `controller` package.
   
## 4. Running the Application
2. Navigate to the project directory.
3. Run the following command to build the project: `mvn clean install`
4. Run the application using: `mvn spring-boot`
5. Open Postman and make a GET request to: `http://localhost:8080/greeting`
6. Test with a custom name by adding a query parameter: `http://localhost:8080/greeting?name=Name`

## Screenshots
![image](https://github.com/user-attachments/assets/54171b43-b863-4378-b580-746baed7bb37)
![image](https://github.com/user-attachments/assets/f4879350-b223-4087-899e-b8976d8db69d)




