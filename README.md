# Basic-Calculator-
This basic calculator works on the basics of html,css and javascript.


# Simple Calculator Web Application

This is a basic implementation of a calculator web application using HTML, CSS, and JavaScript. The calculator allows users to perform arithmetic operations such as addition, subtraction, multiplication, and division.

## How to Use

1. Open the `calculator.html` file in a web browser.

2. The calculator user interface will be displayed with a 3x4 grid of buttons representing numbers (0-9) and arithmetic operators (+, -, *, /).

3. Click on the number buttons to enter numeric values.

4. Click on the operator buttons to perform arithmetic operations.

5. The input display area, labeled "0" initially, will show the numbers and calculation results as you interact with the calculator.

6. To perform calculations, follow these steps:
   - Enter the first number using the number buttons.
   - Click on an arithmetic operator button to select the desired operation (+, -, *, /).
   - Enter the second number using the number buttons.
   - Click on the "=" button to get the result.

7. To clear the input display, click on the "c" button.

8. The calculator will prevent multiple consecutive operators, ensuring correct input.

## HTML Structure

- The HTML document begins with the opening `<html>` tag, followed by the `<head>` section.

- The `<head>` section contains meta-information about the document, including CSS styles for the calculator's appearance.

## CSS Styles

- The CSS styles are used to define the appearance of the calculator user interface.

- The `#main` selector styles the main calculator container, setting its width, height, background color, font, size, weight, style, and box-shadow.

- The `input` selector styles the number buttons, setting their width, height, font size, and margin.

- The `#eee` selector styles the input display area, where numbers and calculation results are displayed.

## JavaScript Functions

- The JavaScript code includes four functions (`add()`, `sub()`, `di()`, and `mul()`) that handle arithmetic operations.

- Each function checks the last character of the input display to prevent multiple consecutive operators, ensuring valid input.

## Calculator Buttons

- The calculator buttons are created using `<input>` elements with the `type="button"` attribute.

- Each button has a specific value (number, operator, or "c" for clearing) and an `onclick` attribute that triggers the corresponding JavaScript function when clicked.

## Input Display

- The input display area is a `<input>` element with the `type="text"` attribute and the `id="eee"`.

- It is where the numbers and calculation results are displayed to the user.

Enjoy using this simple calculator web application to perform basic arithmetic calculations in your web browser!

Please note that this calculator is a basic implementation and may not handle more complex operations or error handling. It is intended for educational purposes and to demonstrate a simple calculator user interface.

Images

![calc](https://github.com/sandipmalii/Basic-Calculator-/assets/128310990/38059710-86fc-4a2d-97a1-8266e2ef03c5)

