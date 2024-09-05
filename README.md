# Random Password Generator

This is a simple **Random Password Generator** that generates secure passwords and allows users to copy them to their clipboard. The generated passwords include uppercase letters, lowercase letters, numbers, and special symbols. 

## Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [How to Use](#how-to-use)
- [License](#license)

## Features

- Generates a random password of specified length (12 characters by default).
- Ensures that the password includes at least one uppercase letter, one lowercase letter, one number, and one special character.
- Allows users to copy the generated password to the clipboard.
- Responsive design for various screen sizes.

## Technologies Used

- **HTML5**: Structuring the web content.
- **CSS3**: Styling the layout and design.
- **JavaScript**: Implementing the password generation and copy functionality.

## How to Use

1. **Generate a Password**:
   - Click on the **Generate Password** button, and a random secure password will be displayed in the input field.

2. **Copy the Password**:
   - After generating the password, click on the **Copy** icon next to the password field to copy it to your clipboard.

### Example Steps:

1. Load the HTML page in your browser.
2. Click the "Generate Password" button to create a password.
3. Click the copy icon to copy the generated password.

### JavaScript (`script.js`):

- **`createPassword()`**: Generates a 12-character random password containing uppercase, lowercase, numbers, and symbols.
- **`copyPassword()`**: Copies the generated password to the clipboard using the `document.execCommand` method.

### CSS (`style.css`):

The CSS styles define a modern, clean design. It makes the generator responsive, aligning buttons, text fields, and images properly across devices.

### HTML (`index.html`):

The structure includes an input field to display the password, a "Generate Password" button, and an image acting as a copy button.

## License

This project is licensed under the MIT License.




