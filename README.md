# Car Rental Company

Welcome to the **Car Rental Company** project! This repository contains the source code for a simple car rental management system written in **Java**. The system allows users to manage a fleet of rental cars, track availability, and calculate rental costs.

## Features

- Add new cars to the rental fleet.
- Remove cars from the fleet.
- View all available cars.
- Rent a car and calculate the rental cost based on the rental duration.
- Handle invalid inputs and manage error cases gracefully.

## Getting Started

### Prerequisites

To run this project, you will need:

- **Java Development Kit (JDK)** installed (version 8 or higher).
- Basic understanding of Java programming.

### Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/XristinaMast/Car-Rental-Company.git
   ```

2. **Navigate to the project directory**:

   ```bash
   cd Car-Rental-Company
   ```

3. **Compile the Java files**:

   If you have `javac` installed:

   ```bash
   javac CarRentalCompany.java
   ```

4. **Run the program**:

   Once the project is compiled, you can run the program:

   ```bash
   java CarRentalCompany
   ```

### Usage

After running the program, you will interact with a simple menu system that allows you to perform the following actions:

- **View available cars**: Displays the list of all cars that are currently available for rent.
- **Add a car**: Allows the admin to add new cars to the fleet.
- **Remove a car**: Removes a car from the available inventory.
- **Rent a car**: Choose a car and specify how many days you'd like to rent it for. The system calculates the total rental cost.
  
### Example Interaction

```
Welcome to the Car Rental Company!
1. View available cars
2. Add a new car
3. Remove a car
4. Rent a car
5. Exit

Choose an option: 1
Available cars:
- BMW 320i
- Ford Focus

Choose an option: 4
Enter car to rent: BMW 320i
Enter number of days: 5
Rental cost for BMW 320i: $250

Choose an option: 5
Exiting...
```

### Project Structure

```
Car-Rental-Company/
├── Car.java                   # Car class definition
├── CarRentalCompany.java       # Main Java class with the rental logic
├── README.md                   # Documentation
└── other Java files...
```
