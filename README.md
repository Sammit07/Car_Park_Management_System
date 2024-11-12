# Car Park Management System

## Project Overview

The Car Park Management System is a Java-based GUI application designed to help users efficiently manage parking spots and parked cars. This system allows for adding and removing parking spots, parking and removing cars, and finding cars based on their registration number or make. The application provides a user-friendly graphical interface that enables real-time updates and easy interaction.

## Features

- **Add Parking Spots**: Allows users to add new parking spots with a unique ID.
- **Delete Parking Spots**: Enables users to delete an existing parking spot if it is unoccupied.
- **List All Parking Spots**: Displays all parking spots, their occupancy status (occupied or vacant), and provides a summary of total, occupied, and available spots.
- **Park a Car**: Allows users to park a car in a specified spot by entering the spot ID and car details (registration number, make, model, and year).
- **Find Car by Registration Number**: Searches for a car based on its registration number and shows the parking spot and parking duration.
- **Remove Car by Registration Number**: Removes a car from its spot based on the registration number.
- **Find Cars by Make**: Lists all cars of a specified make along with their parking spots, details, and parking durations.
- **Reset Car Park**: Clears all parked cars, making all spots vacant.
- **Exit Application**: Safely exits the application with a confirmation message.

## Technologies Used

- **Programming Language**: Java
- **User Interface**: Java Swing GUI components

## Project Structure

- **Application.java** - The main class that initializes and launches the application.
- **Car.java** - Contains the attributes and methods for managing car details, including registration number, make, model, and year.
- **CarPark.java** - Manages the parking spots and operations related to adding, removing, and querying spots and cars.
- **CarParkGUI.java** - Provides the graphical user interface for users to interact with the car park system.
- **ParkingSpot.java** - Defines the parking spot properties and status (occupied or vacant).
- **Supporting Classes** - Additional classes to handle various GUI button listeners and utilities for user interactions.

## Getting Started

### Prerequisites

To run this project, you need:
- **Java Development Kit (JDK)** 8 or higher installed on your computer.

### Installation and Setup

1. **Open the Project in Your IDE**:
   - Launch your preferred Java IDE (e.g., IntelliJ IDEA, Eclipse, or BlueJ).
   - Import the project files into the IDE.

2. **Compile and Run the Application**:
   - Locate `Application.java` in your IDE.
   - Compile and run the `main` method in `Application.java` to start the application.

   - For **BlueJ** users:
     - Open the project in BlueJ.
     - Right-click on the `Application` class.
     - Select `void main(String[] args)` to run the application.

## Usage Instructions

### Main Window Overview

- **Title Panel**: Displays "Parking Spot System" at the top of the window.
- **Control Panel**: Located on the left side, containing buttons for various operations.
- **Parking Panel**: Displays all parking spots with their status and details.

### Control Buttons and Their Functions

- **Add Parking Spot**: Allows you to add a new spot by entering a unique ID (e.g., A001).
- **Delete Parking Spot**: Lets you delete an unoccupied spot by entering its ID.
- **List All Parking Spots**: Shows all spots with their occupancy status (vacant or occupied).
- **Park a Car**: Prompts for car details and spot ID to park a car in an available spot.
- **Find Car by Registration Number**: Searches and locates a car based on its registration number.
- **Remove Car by Registration Number**: Removes a car from its spot using the registration number.
- **Find Cars by Make**: Lists all cars of a specified make and their details.
- **Reset Car Park**: Clears all parked cars, making all spots vacant.
- **Exit**: Safely closes the application with a confirmation message.

### Notes for Users

- **Parking Spot ID Format**: Must be an uppercase letter followed by three digits (e.g., A001).
- **Car Registration Format**: An uppercase letter followed by four digits (e.g., A1234).
- **Car Year**: Must be between 2004 and 2024.
- Ensure all inputs are correctly formatted to avoid errors.
- Each parking spot and car must have a unique ID.
