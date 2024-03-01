# Kotlin Calculator App

## Alert: The application is under development. You may encounter some bugs while using it!




## Welcome to the Kotlin Calculator App repository! This simple calculator app is designed to perform basic arithmetic operations. Feel free to explore the source code and make any improvements or modifications.


## Getting Started

These instructions will help you set up and run the calculator app on your local machine.

### Prerequisites

Make sure you have the following installed:

- Android Studio
https://developer.android.com/studio

- Kotlin Plugin for Android Studio

### Installation

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/DaviDM2005/Calculator-App.git
   ```

2. Open the project in Android Studio.

3. Build and run the app on an Android emulator or a physical device.

## Features

- Addition, subtraction, multiplication, and division operations
- Decimal point support
- Clear button to reset the input
- Equal button to calculate the result

## Usage

1. Launch the app on your Android device or emulator.

2. Input numbers and perform operations using the provided buttons.

3. Press the equal button to see the result of the calculation.

4. Use the clear button to reset the input and start a new calculation.

## Code Overview

The main functionality of the app is implemented in the `MainActivity` class, which handles button clicks and performs arithmetic operations. The XML layout file (`activity_main.xml`) defines the user interface elements.

Key methods in `MainActivity`:

- `onDigit(view: View)`: Appends the clicked digit to the input text.
- `onClear(view: View)`: Clears the input text.
- `onDecimalPoint(view: View)`: Appends a decimal point to the input text.
- `onOperator(view: View)`: Appends the clicked operator to the input text.
- `onEqual(view: View)`: Calculates the result of the expression.


### You can also download apk:
https://drive.google.com/file/d/1eSU6jxVuu8VsOkmKu5XTm-8UDtrCnkkn/view?usp=sharing

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

**MIT License**

```
Copyright (c) 2024 Davit

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

Feel free to copy and use this in your README.md file. If you have any more requests or questions, let me know!
