# Password Generator

A simple and intuitive password generator that allows you to create strong and secure passwords with customizable options. This tool helps you generate passwords of varying lengths, including upper and lower case letters, numbers, and special symbols.

## Features

- **Customizable Length**: Choose password length from 1 to 20 characters.
- **Character Inclusion**: Include or exclude uppercase letters, lowercase letters, numbers, and special symbols.
- **Password Strength Indicator**: Visual indicator to show the strength of the generated password.
- **Copy to Clipboard**: Easily copy the generated password to your clipboard with a single click.

## Demo

You can see the application in action with the following demo link: [Demo Link](#)

## Installation

To get a local copy up and running, follow these simple steps:

1. **Clone the repo**
    ```sh
    git clone https://github.com/mkraj-7838/Password-Generator.git
    ```

2. **Navigate to the project directory**
    ```sh
    cd password-generator
    ```

3. **Open `index.html` in your browser**

## Usage

1. Open the `index.html` file in your preferred web browser.
2. Adjust the password length using the slider.
3. Select the character types you want to include in your password by checking the corresponding checkboxes.
4. Click the 'Generate Password' button.
5. Copy the generated password to your clipboard by clicking the copy button.

## Code Overview

### HTML

The `index.html` file contains the structure of the password generator. It includes a range input for setting password length, checkboxes for character options, and a display area for the generated password.

### CSS

The `style.css` file styles the components of the password generator, ensuring a user-friendly and visually appealing interface.

### JavaScript

The `index.js` file contains all the logic for the password generator, including functions to:
- Generate random characters (uppercase, lowercase, numbers, symbols).
- Shuffle the generated password for added security.
- Handle user inputs and display the generated password.
- Copy the generated password to the clipboard.
- Update the strength indicator based on the selected options.

