# My Spring Boot Application

This is a simple Spring Boot web application that demonstrates the basic structure and functionality of a Spring Boot project.

## Project Structure

```
my-spring-boot-app
├── src
│   ├── main
│   │   ├── java
│   │   │   └── com
│   │   │       └── example
│   │   │           └── MySpringBootAppApplication.java
│   │   └── resources
│   │       ├── application.properties
│   │       └── templates
│   │           └── index.html
│   └── test
│       └── java
│           └── com
│               └── example
│                   └── MySpringBootAppApplicationTests.java
├── pom.xml
└── README.md
```

## Prerequisites

- Java 11 or higher
- Maven

## Setup Instructions

1. Clone the repository:
   ```
   git clone <repository-url>
   cd my-spring-boot-app
   ```

2. Build the project:
   ```
   mvn clean install
   ```

3. Run the application:
   ```
   mvn spring-boot:run
   ```

4. Open your browser and navigate to `http://localhost:8080` to see the application in action.

## Usage

This application serves a simple web page using Thymeleaf. You can modify the `index.html` file located in `src/main/resources/templates` to change the content displayed on the main page.

## Testing

To run the tests, use the following command:
```
mvn test
```

## License

This project is licensed under the MIT License. See the LICENSE file for more details.