# Smart Contact Manager Application

Smart Contact Manager application built using Spring Boot and Thymeleaf. The application is designed to help users manage groups and contacts efficiently.


![1685445382980](image/README/1685445382980.png)

## Features

1. User Authentication and Authorization:
   * Secure user registration and login functionality.
   * Role-based access control for different user types (admin and regular users).
2. Group Management:
   * Create, update, and delete groups.
   * Assign contacts to groups.
3. Contact Management:
   * Create, update, and delete contacts.
   * Assign contacts to multiple groups.
   * Search Contact, Using Edit Distance NLP model.
4. User Dashboard:
   * Displays a summary of the user's groups and contacts.
   * Provides quick access to manage groups and contacts.
   * Presents relevant statistics and insights.

## Technology Stack

The Smart Contact Manager application is built using the following technologies:

* Java: The programming language used to write the application logic.
* Spring Boot: The framework used for building the backend RESTful APIs and managing dependencies.
* Thymeleaf: The server-side Java template engine used for rendering dynamic web pages.
* Spring Security: The library used for authentication and authorization.
* JPA Data: The Object-Relational Mapping (ORM) framework used for database access.
* MySQL: The relational database used to store groups, contacts, and user information.
* HTML/CSS/JavaScript: The front-end technologies used to create the user interface.
* Bootstrap: The CSS framework used for responsive and mobile-first design.

## Getting Started

To get started with the Smart Contact Manager application, follow these steps:

1. Clone the repository: `git clone https://github.com/sid41x4/smartcontact.git`
2. Navigate to the project directory: `cd smartcontact`
3. Configure the database connection in the `application.properties` file.
4. Build the project using Maven: `mvn clean install`
5. Run the application: `mvn spring-boot:run`
6. Access the application in your web browser: `http://localhost:8080`

## Folder Structure

The folder structure of the Smart Contact Manager application is as follows:

* `src/main/java`: Contains the Java source code.
  * `com.example.smartcontact`: Main package for the application.
    * `web`: Contains the controllers for handling HTTP requests.
    * `models`: Contains the model classes representing entities.
    * `dao`: Contains the interfaces for database access.
    * `service`: Contains the service classes for business logic.
    * `security`: Contains security-related classes.
    * `SmartContactManagerApplication.java`: The main application class.
* `src/main/resources`: Contains the resource files.
  * `application.properties`: Contains application-specific configuration.
  * `templates`: Contains Thymeleaf HTML templates.
  * `static`: Contains static resources such as CSS and JavaScript files.

## Contact

feel free to contact me at  `aitouakoursaid@gmail.com`.
