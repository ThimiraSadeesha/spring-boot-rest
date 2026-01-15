# Spring Boot REST API (CRUD Operations)

A RESTful API built with Spring Boot.

## Technologies

- Java 21
- Spring Boot 3.4.5
- Spring Data JPA
- MySQL
- Maven
- Jakarta Validation

## Prerequisites
- JDK 21 or later
- Maven 3.9+
- MySQL

## Database Configuration

The application uses environment variables for configuration. You can set them in your terminal or in a `.env` file (if using a tool like `dotenv-spring`):

```bash
    export DB_NAME=your_database
    export DB_USER=your_username
    export DB_PASSWORD=your_password
    export DB_HOST=localhost
    export DB_PORT=3306

```

## Building and Running the Application

1. Clone the repository
2. Navigate to the project directory
3. Build the project:
   ```bash
   mvn clean install
   ```
4. Run the application:
   ```bash
   mvn spring-boot:run
   ```

The application will start on port 8080.
