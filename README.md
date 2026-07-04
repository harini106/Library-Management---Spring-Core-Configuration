# Library Management - Spring Core Configuration

## Overview

This project demonstrates the basic configuration of a Spring application using XML-based bean configuration. It is a simple library management example that defines and loads Spring beans for a service and a repository.

## Technologies Used

- Java
- Spring Framework (Spring Core)
- Maven
- XML Configuration

## Project Structure

```text
LibraryManagement/
│
├── pom.xml
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/
│   │   │       └── library/
│   │   │           ├── MainApp.java
│   │   │           ├── service/
│   │   │           │   └── BookService.java
│   │   │           └── repository/
│   │   │               └── BookRepository.java
│   │   └── resources/
│   │       └── applicationContext.xml
```

## Features

- Configures Spring using an XML configuration file.
- Defines `BookService` and `BookRepository` as Spring beans.
- Loads the Spring Application Context.
- Retrieves Spring-managed beans and executes their methods.

## Dependencies

- Spring Context 5.3.30

## How to Run

1. Clone the repository.
2. Open the project in your preferred IDE.
3. Allow Maven to download the required dependencies.
4. Run `MainApp.java`.

## Expected Output

```text
Book Service is working...
Book Repository is working...
```

## Learning Outcomes

- Create a Maven-based Spring project.
- Configure beans using `applicationContext.xml`.
- Understand XML-based dependency injection.
- Load and use the Spring Application Context.
- Retrieve beans from the Spring IoC container.

## Author

**Harini**
