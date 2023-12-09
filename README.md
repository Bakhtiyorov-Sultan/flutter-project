# calc_demo
Overview
Welcome to the Calculator App, a simple yet powerful calculator built using Flutter. This application consists of three main files: calc-button.dart, calculator-view.dart, and main.dart. This README provides an overview of each file's purpose and how they contribute to the functionality of the Calculator App.

Files
1. calc-button.dart
calc-button.dart is a crucial component of the Calculator App, responsible for creating the individual buttons used for numeric input, operations, and other essential functions. The file encapsulates the design and behavior of each button, ensuring a consistent and responsive user interface.

Key features of calc-button.dart:

Reusable Components: Define reusable button components with customizable attributes such as text, color, and action.
Event Handling: Implement event handling to capture user interactions like button presses, enabling seamless integration with the calculator logic.
2. calculator-view.dart
calculator-view.dart serves as the main user interface (UI) for the Calculator App. It orchestrates the arrangement and interaction of buttons, displays the input and output, and provides a cohesive user experience.

Key features of calculator-view.dart:

Layout Structure: Define the layout of the calculator, including the arrangement of numeric buttons, operators, and other essential components.
User Input Handling: Capture user input and display it on the calculator screen, ensuring a responsive and real-time user experience.
Integration with Calculator Logic: Connect the UI elements to the underlying calculator logic to perform arithmetic operations and update the display accordingly.
3. main.dart
main.dart is the entry point of the Calculator App, responsible for initializing the Flutter application and defining the overall structure of the user interface.

Key features of main.dart:

App Initialization: Set up the Flutter application, configure dependencies, and define the root widget for the Calculator App.
Integration with Calculator View: Instantiate the CalculatorView widget, linking the UI to the core functionality of the calculator.
