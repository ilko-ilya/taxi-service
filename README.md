# Taxi Service

## Summary
Taxi Service is a web application that allows users to manage drivers, cars, and manufacturers in a taxi service system.

## Functionality
The application provides the following features:

- Driver management: adding, deleting, updating, and registering drivers.
- Car management: adding, deleting, and updating cars.
- Manufacturer management: adding, deleting, and updating manufacturers.
- Retrieving a car by driver ID.

## Project Structure
The project follows a standard MVC (Model-View-Controller) architecture and is structured as follows:

- `src/main/java`: Contains the Java source code.
- `src/main/resources`: Contains the configuration files and resources.
- `src/main/webapp`: Contains the web application files (JSP, CSS, JavaScript).

## Technologies Used
The project is built using the following technologies:

- Java-17 (https://docs.oracle.com/en/java/javase/17/)
- Servlets 
- JSP
- MySQL
- JDBC
- Maven
- Tomcat
- JSTL
- Html
- Git

## Getting Started
To run the project on your local machine, follow these steps:

1. Set up a MySQL database.
2. Clone the project repository.
3. Configure the database connection in the ConnectionUtil class:
   - Open the src/main/taxi/util/ConnectionUtil.java file.
   - Locate the ConnectionUtil class.
   - Replace the placeholder values in the URL, USERNAME, and PASSWORD fields with the actual database connection details.
   - Save the file.
4. Build the project using Maven: `mvn clean package`.
5. Deploy the WAR file to a Tomcat 9.0.75 server.
6. Access the application in your web browser: `http://localhost:8080/taxi`.

## Additional Sections
Feel free to add any additional sections that you think would be helpful for your project.

