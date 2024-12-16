
# 08 TypeScript and OOP: Vehicle Builder

## Description
A TypeScript command-line application that builds and uses cars, trucks, and motorbikes, with additional options for each vehicle type. The application allows users to create a new vehicle or select an existing one. Once a vehicle is created or selected, users can perform specific actions with the vehicle. After each action, users are returned to the actions menu until they choose to exit the application.

## Features

- **Vehicle Creation**: Allows users to create new vehicles by entering vehicle details such as type (car, truck, motorbike).
- **Vehicle Selection**: Users can select an existing vehicle to perform actions.
- **Vehicle Actions**: Once a vehicle is created or selected, users can perform different actions with the vehicle, with the results displayed in the command-line.
- **Menu System**: Users are returned to the actions menu after each action, providing a loop until the user chooses to exit.

## Technologies Used
- TypeScript
- Object-Oriented Programming (OOP) principles
- Node.js for command-line interaction

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/vehicle-builder.git
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Run the application:

   ```bash
   npm start
   ```

## Usage

1. Choose whether to create a new vehicle or select an existing one.
2. If creating a new vehicle, select the type (car, truck, motorbike) and enter the required details.
3. Once the vehicle is created or selected, perform actions on the vehicle (e.g., start the engine, check fuel, etc.).
4. After each action, the application will return to the actions menu, allowing you to perform additional actions until you choose to exit.

## Contributing

Feel free to fork the repository, submit issues, or open pull requests. Contributions are welcome!

## License

This project is licensed under the MIT License.
```

### User Story

```md
AS a developer
I WANT to update an existing application to include additional vehicle types
SO THAT I am able to comprehend and work with existing code bases.
```

## Acceptance Criteria

```md
GIVEN a command-line application that accepts user input
WHEN I am prompted to create a new vehicle or select an existing vehicle
THEN I can choose between the two options

WHEN I am prompted to choose the vehicle type during creation
THEN I can choose between car, truck, and motorbike

WHEN I am prompted for details about the vehicle
THEN I can enter the vehicle information

WHEN I have entered all the vehicle information
THEN I can use the created vehicle

WHEN I select an existing vehicle
THEN I can use the selected existing vehicle

WHEN I have created a new vehicle or selected an existing vehicle
THEN I can perform actions with that vehicle

WHEN I perform an action with a vehicle
THEN I see the result of the action in the command-line

WHEN I complete the process of performing an action
THEN I can perform additional actions until I choose to exit