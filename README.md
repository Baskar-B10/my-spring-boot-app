# My Spring Boot Application

This is a Spring Boot application that demonstrates the use of Spring Security. The application includes a simple home page and is structured to provide a clear separation of concerns.

## Project Structure

```
my-spring-boot-app
├── src
│   ├── main
│   │   ├── java
│   │   │   └── com
│   │   │       └── example
│   │   │           └── app
│   │   │               ├── Application.java
│   │   │               ├── config
│   │   │               │   └── SecurityConfig.java
│   │   │               └── controller
│   │   │                   └── HomeController.java
│   │   └── resources
│   │       ├── application.yml
│   │       └── templates
│   │           └── index.html
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

1. **Clone the repository**:
   ```
   git clone <repository-url>
   cd my-spring-boot-app
   ```

2. **Build the project**:
   ```
   mvn clean install
   ```

3. **Run the application**:
   ```
   mvn spring-boot:run
   ```

4. **Access the application**:
   Open your web browser and navigate to `http://localhost:8080`.

## Usage

- The home page is accessible at the root URL (`/`).
- Security configurations are defined in `SecurityConfig.java`, which specifies which endpoints are secured.
- The application uses Thymeleaf for rendering the home page, which is defined in `index.html`.

## Dependencies

This project uses the following dependencies:
- Spring Boot
- Spring Security
- Thymeleaf

Make sure to check the `pom.xml` file for the complete list of dependencies and their versions.