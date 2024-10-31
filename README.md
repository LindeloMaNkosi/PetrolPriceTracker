# Petrol Price Tracker Application

This Java application tracks and displays petrol prices in different cities over multiple years. Users can select a city and year to view the corresponding petrol price using a graphical user interface.

## Features

- **City and Year Selection**: Select a city and year to view petrol prices.
- **Data Display**: Displays petrol prices for Johannesburg, Durban, and Cape Town for the years 2017, 2018, and 2019.
- **GUI Interface**: Built using Java Swing components like `JComboBox`, `JList`, and `JOptionPane`.
- **Menu System**: Includes menu options for submitting data and displaying a report.

## Skills and Lessons Learned

- **Java Swing**: Creating a user-friendly GUI using Swing components. Learned to handle events and manage layouts.
- **Object-Oriented Programming (OOP)**: Understanding and implementing classes and objects. Learned to create constructors, getters, and handle object copying.
- **Data Storage**: Storing and retrieving data using a 2D array. Simulated file handling by using arrays to manage data.
- **Event Handling**: Managing user interactions through buttons and menu items. Implemented event listeners to handle actions.
- **Code Organization**: Structured code effectively by separating concerns into different methods and classes.

## Program Notes

- **Petrol Class**: Represents petrol price data for a given year and city. It includes methods to get year, city, and price.
- **PetrolApplication Class**: The main application class that sets up the GUI and handles user interactions. It initializes petrol data and manages the display logic.
- **Data Initialization**: Petrol prices are stored in a 2D array, allowing easy access and display based on user selections.
- **User Interaction**: Users can select a city and year from the GUI components and click the submit button to display the petrol price.

## Setup and Installation

1. **Clone the Repository**:
   ```sh
   git clone https://github.com/yourusername/PetrolPriceTracker.git
