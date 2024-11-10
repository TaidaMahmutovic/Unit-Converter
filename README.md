
# Unit Converter Console Application

## Overview

This Unit Converter Console Application is a simple, interactive tool that enables users to convert values between different units of measurement. It supports conversions for **Length**, **Weight**, and **Temperature** and provides an intuitive, menu-driven interface. This project is implemented in three languages: **C#**, **JavaScript (Node.js)**, and **Python**.

## Features

- **Length Conversion**: Converts between meters, kilometers, miles, feet, and inches.
- **Weight Conversion**: Converts between grams, kilograms, pounds, and ounces.
- **Temperature Conversion**: Converts between Celsius, Fahrenheit, and Kelvin.
- **Menu-Driven Interface**: Provides a step-by-step console interface for easy use.
- **Multiple Language Support**: Implemented in C#, JavaScript, and Python for versatility.

---

## Getting Started

### Prerequisites

To run the application, you need:
- **C#**: .NET SDK (6.0 or higher recommended)
- **JavaScript**: Node.js installed
- **Python**: Python 3.6 or higher installed

### Running the Application

Each version of the application can be run from the console. Here’s how to execute it in each language:

#### C#

1. Navigate to the directory containing the C# code.
2. Run the following commands:
   ```sh
   dotnet run
   ```

#### JavaScript (Node.js)

1. Navigate to the directory containing the JavaScript file.
2. Run:
   ```sh
   node app.js
   ```

#### Python

1. Navigate to the directory containing the Python file.
2. Run:
   ```sh
   python app.py
   ```

---

## Usage

When the application starts, it displays a main menu prompting the user to select a conversion type (Length, Weight, or Temperature). After choosing a type, users input the value and select source and target units. The program then performs the conversion and displays the result.

### Example

1. User selects **Length Conversion**.
2. Enters a value (e.g., `100` meters).
3. Chooses conversion (e.g., **Meters to Kilometers**).
4. Result (e.g., `0.1` kilometers) is displayed.

---

## Code Structure

The project is designed to be modular, with separate functions/methods handling conversions for each unit type. Here’s a breakdown of the structure in each language:

### C#

- **Main Program**: Contains the main menu and handles user inputs.
- **LengthConversion, WeightConversion, TemperatureConversion** methods: Perform specific conversions based on unit choice.
- **Conversion Logic**: Each method uses formulas or conversion factors to return results.

### JavaScript (Node.js)

- **Functions for Each Type**: `lengthConversion`, `weightConversion`, and `temperatureConversion` each handle their respective units.
- **Main Function**: `startConversion()` orchestrates the menu flow and calls the appropriate conversion function based on user input.
- **Unit Maps**: Predefined dictionaries in each function store conversion factors for easy reference.

### Python

- **Functions for Each Type**: Similar to JavaScript, there are separate functions: `length_conversion`, `weight_conversion`, and `temperature_conversion`.
- **Main Function**: `main()` prompts user input, invokes the necessary conversion, and displays results.
- **Unit Dictionary**: A dictionary for each conversion type stores units and factors for quick calculations.

---

## Supported Conversions

Each unit type supports several standard conversions. Below is a list of supported conversions:

- **Length**: Meters, Kilometers, Miles, Feet, Inches
- **Weight**: Grams, Kilograms, Pounds, Ounces
- **Temperature**: Celsius, Fahrenheit, Kelvin

---

## How Conversions Work

The application calculates conversions using predefined formulas or factors:

- **Length and Weight**: Use a ratio-based system where each unit is converted by a factor relative to another unit.
- **Temperature**: Uses formula-based conversions (e.g., Celsius to Fahrenheit: \((°C * 9/5) + 32\)).

Each conversion function determines the result by applying the appropriate formula or factor.

---

## Future Enhancements

Potential improvements include:
- **Additional Units**: Expanding support to volume, area, or speed conversions.
- **Graphical Interface**: Creating a GUI for a more user-friendly experience.
- **Extended Language Support**: Adding more languages, like Java or Ruby, to broaden compatibility.

---

## Contributing

Contributions to this project are welcome! If you’d like to improve the code or add new features, please submit a pull request or open an issue.

---

## License

This project is open-source and licensed under the MIT License.
