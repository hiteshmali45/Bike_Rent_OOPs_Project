# Bike Rental System Project

## Overview
This project is an OOP-based Bike Rental System, designed and implemented in Python. It provides users with options to rent bikes on an hourly, daily, or weekly basis and includes additional features such as family discounts and user account management.

## Features

- **Renting Options**:
  - Hourly rental option: Ideal for short-term users.
  - Daily rental option: Suitable for longer single-day use.
  - Weekly rental option: Offers better pricing for extended use.

- **Family Rental**:
  - Users can rent multiple bikes at a discounted rate if renting 3 to 5 bikes.

- **Object-Oriented Design**:
  - Implemented with classes such as `BikeRental`, `Customer`, and related OOP concepts.

## Project Structure

- `BikeRental` class:
  - Contains methods to display available bikes, rent bikes (hourly, daily, or weekly), and process bike returns.

- `Customer` class:
  - Tracks customer details, rental time, rental basis, and the number of bikes rented.

- Main execution file:
  - Handles user input, rental process, and displays options for users.

## How to Run the Project
Clone this repository: git clone https://github.com/hiteshmali45/Bike_Rent_OOPs_Project

Open the Jupyter Notebook: jupyter notebook Bike_Rent_OOPs_Project.ipynb

Follow the steps in the notebook to run the solution and understand the logic.
## Example Usage
When you run the project, you will be presented with a menu of options:

- Display available bikes
- Rent a bike (hourly, daily, or weekly)
- Return a bike
- Apply for family rental discount (if applicable)

Sample Output:
```
Welcome to the Bike Rental Shop!
Please choose an option:
1. Display available bikes
2. Rent a bike on hourly basis
3. Rent a bike on daily basis
4. Rent a bike on weekly basis
5. Return a bike
6. Exit
```

## Future Enhancements
- Add a database to store customer rental history.
- Implement a graphical user interface (GUI).
- Introduce loyalty rewards for frequent users.

## Acknowledgments
- Inspired by common bike rental systems.
- Developed as part of a learning project to strengthen OOP and Python skills.


