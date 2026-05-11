# Sample Spring Boot Application

This is a simple Spring Boot application demonstrating basic REST endpoints.

## Features

- REST API endpoints
- Spring Data JPA integration
- H2 in-memory database
- Maven build system

## Prerequisites

- Java 17 or higher
- Maven 3.6.0 or higher

## Build and Run

### Build the application:
```bash
mvn clean package
```

### Run the application:
```bash
mvn spring-boot:run
```

The application will start on `http://localhost:8080`

## API Endpoints

- `GET /` - Welcome message
- `GET /hello?name=YourName` - Personalized greeting

## H2 Console

Access the H2 database console at: `http://localhost:8080/h2-console`

## Project Structure

```
src/
├── main/
│   ├── java/com/example/
│   │   ├── Application.java
│   │   └── controller/
│   │       └── HelloController.java
│   └── resources/
│       └── application.properties
└── test/
```
