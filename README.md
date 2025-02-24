# Train Management System (TMS)

## Project Overview

The Train Management System (TMS) is a console-based application designed to manage trains, passengers, and stations. It provides functionalities for adding, removing, and listing these entities. The system is built using Java and is intended to be run in a console environment.

## Features

- **Add Train**: Add a new train with details like train number, destination, and capacity.
- **Add Passenger**: Add a new passenger to a specific train.
- **Add Station**: Add a new station with details like station code, station name, and location.
- **List Trains**: Display a list of all trains with their details.
- **List Passengers**: Display a list of all passengers with their details.
- **List Stations**: Display a list of all stations with their details.
- **Remove Train**: Remove a train and all associated passengers.

## Prerequisites

Before running the project, ensure you have the following installed:

- **Java Development Kit (JDK)**: Version 8 or higher.
- **Java Runtime Environment (JRE)**: To run the compiled Java application.
- **Build Automation Tool**: Apache Ant (optional, for build automation).

## Installation and Setup

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/LeahAW00/Train-Management-Systemm
   
2. Compile the Project:
   - If using Apache Ant, run:
          ant compile
     
   - Alternatively, you can compile the Java files manually:
          javac -d build/classes src/*.java
     

3. Run the Project:
   - If using Apache Ant, run:
          ant run
     
   - Alternatively, you can run the compiled Java application:
          java -cp build/classes TrainManagementSystem
     

## Usage

1. Main Menu:
   - Upon running the application, you will be presented with a menu-driven interface.
   - Choose the appropriate option to add trains, passengers, or stations, list existing entities, or remove trains.

2. Adding a Train:
   - Select option 1 from the menu.
   - Enter the train number, destination, and capacity when prompted.

3. Adding a Passenger:
   - Select option 2 from the menu.
   - Enter the passenger name and the train number they are boarding.

4. Adding a Station:
   - Select option 3 from the menu.
   - Enter the station code, station name, and location.

5. Listing Entities:
   - Select options 4, 5, or 6 to list all trains, passengers, or stations, respectively.

6. Removing a Train:
   - Select option 7 from the menu.
   - Enter the train number of the train you wish to remove.

7. Exiting the System:
   - Select option 8 to exit the application.

## Testing

The project includes unit tests for critical functionalities. To run the tests:

1. Using Apache Ant:
      ant test
   

2. Manually:
   - Ensure JUnit is set up in your environment.
   - Run the test classes using your preferred IDE or command line.

## Build Automation

The project includes an build.xml file for Apache Ant, which automates the build process. The following targets are available:

- clean: Cleans the build directory.
- compile: Compiles the source code.
- test: Runs the unit tests.
- package: Packages the application into a JAR file.
- run: Runs the application.

## Documentation

- SRS Documentation: The Software Requirements Specification (SRS) document is included in the repository, detailing the system's requirements, design, and functionality.
- UML Diagrams: The repository includes UML diagrams (class diagram, use case diagram, sequence diagram) to visualize the system's structure and behavior.

## Contributing

Contributions are welcome! If you'd like to contribute, please fork the repository and create a pull request with your changes.


## Acknowledgments

- Java Documentation: For providing comprehensive documentation on Java.
- Apache Ant: For simplifying the build process.
- JUnit: For enabling unit testing in Java.
