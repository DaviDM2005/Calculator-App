
Kotlin Calculator App
Welcome to the Kotlin Calculator App repository! This simple calculator app is designed to perform basic arithmetic operations. Feel free to explore the source code and make any improvements or modifications.

Getting Started
These instructions will help you set up and run the calculator app on your local machine.

Prerequisites
Make sure you have the following installed:

Android Studio
Kotlin Plugin for Android Studio
Installation
Clone the repository to your local machine:

bash
Copy code
git clone https://github.com/DaviDM2005/Calculator-App.git
Open the project in Android Studio.

Build and run the app on an Android emulator or a physical device.

Features
Addition, subtraction, multiplication, and division operations
Decimal point support
Clear button to reset the input
Equal button to calculate the result
Usage
Launch the app on your Android device or emulator.

Input numbers and perform operations using the provided buttons.

Press the equal button to see the result of the calculation.

Use the clear button to reset the input and start a new calculation.

Code Overview
The main functionality of the app is implemented in the MainActivity class, which handles button clicks and performs arithmetic operations. The XML layout file (activity_main.xml) defines the user interface elements.

Key methods in MainActivity:

onDigit(view: View): Appends the clicked digit to the input text.
onClear(view: View): Clears the input text.
onDecimalPoint(view: View): Appends a decimal point to the input text.
onOperator(view: View): Appends the clicked operator to the input text.
onEqual(view: View): Calculates the result of the expression.
Customization
Feel free to customize the app by making changes to the code, such as adjusting the UI layout or adding new features.

License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
The app layout uses a simple and clean design for easy usability.
Thank you for checking out the Kotlin Calculator App! If you have any questions or suggestions, feel free to open an issue or contribute to the project.
