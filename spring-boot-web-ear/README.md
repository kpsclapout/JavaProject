# Spring Boot Web EAR Project

This project is a Spring Boot application packaged as an EAR (Enterprise Archive) file. It demonstrates how to create a simple web application using Spring Boot and Thymeleaf.

## Project Structure

```
spring-boot-web-ear
├── src
│   ├── main
│   │   ├── java
│   │   │   └── com
│   │   │       └── example
│   │   │           └── app
│   │   │               ├── Application.java
│   │   │               └── controller
│   │   │                   └── HomeController.java
│   │   ├── resources
│   │   │   ├── application.properties
│   │   │   └── templates
│   │   │       └── index.html
│   └── test
│       └── java
│           └── com
│               └── example
│                   └── app
│                       └── ApplicationTests.java
├── pom.xml
└── README.md
```

## Setup Instructions

1. **Clone the Repository**
   ```
   git clone <repository-url>
   cd spring-boot-web-ear
   ```

2. **Build the Project**
   Use Maven to build the project and generate the EAR file:
   ```
   mvn clean install
   ```

3. **Run the Application**
   You can run the application using the following command:
   ```
   mvn spring-boot:run
   ```

4. **Access the Application**
   Open your web browser and navigate to `http://localhost:8080` to see the home page.

## Usage

This application serves a simple home page using Thymeleaf. You can modify the `index.html` file located in `src/main/resources/templates` to change the content displayed on the home page.

## Testing

Unit tests are included in the project and can be run using:
```
mvn test
```

## Dependencies

The project uses the following key dependencies:
- Spring Boot Starter Web
- Spring Boot Starter Thymeleaf

## Packaging

The project is configured to be packaged as an EAR file, which can be deployed to an application server. Make sure to check the `pom.xml` for the necessary configurations.