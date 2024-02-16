Maven Spring Boot Binary Web Application

This is a Maven Spring Boot project that demonstrates the workflow of using Maven along with Spring Boot to create a web application following the Model-View-Controller (MVC) architecture. The project also includes tests to ensure the functionality of the web application.

Project Structure

The project structure follows the standard Maven layout:

    src/main/java: Contains the Java source code for the web application.
    src/main/resources: Contains configuration files and static resources.
    src/test/java: Contains the test classes for testing the functionality of the application.
    pom.xml: The Maven Project Object Model (POM) file that defines project dependencies, build settings, and plugins.

Running Tests

Tests are located in the src/test/java directory and are executed using the Maven Surefire Plugin. When you run the command mvn test, Maven will compile the test classes, execute them, and generate a report detailing the results.
