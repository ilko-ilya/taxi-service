# Taxi Service

This project is a taxi service application that allows you to add, delete, update, and register drivers, as well as add, delete, and update cars. You can also get a car by driver ID. The project is built using Java, HttpServlet, JDBC, MySQL, and Maven.
## Functionality

The project provides the following functionalities:

- Adding, deleting, updating, and registering drivers.
- Adding, deleting, and updating cars.
- Adding, deleting, and updating manufacturers.
- Retrieving a car by driver ID.

## Getting Started
These instructions will guide you through setting up and running the project on your local machine.

## Prerequisites
- MySQL installed on your computer.
- Java Development Kit (JDK) installed.
- Apache Maven installed.

## Setting up the Database
1. Create a new database for the Taxi Service project.

2. In the project directory, navigate to 'src/main/resources/db.properties file'.

3. Update the following properties in the db.properties file with your MySQL database information:
   - url=jdbc:mysql://localhost:3306/taxi
   - username=your_username
   - password=your_password


## Building and Running the Project
1. Open a command-line interface and navigate to the project directory.

2. Build the project using Maven by running the following command:
   - mvn clean install
3. Start the project by running the following command:
   - mvn tomcat9:run
4. The web application will be deployed on the embedded Tomcat server and can be accessed at http://localhost:8080/taxi


## Additional Information
For more information about the project structure, code organization, and implementation details, please refer to the project's source code and documentation.

## Contributing
Contributions are welcome! If you have any ideas, suggestions, or bug reports, please open an issue or submit a pull request.

---

Feel free to modify and customize this README file according to your project's specific details.

Good luck with your Taxi Service project! If you have any further questions, please let me know.
