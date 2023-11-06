# Password-Generator
# Password Manager Application

This is a Python application that serves as a password manager, allowing users to generate secure passwords, save website credentials, and retrieve them when needed. The application uses the Tkinter library for the user interface and includes functionality for password generation, saving passwords, and searching for saved passwords.

## Table of Contents

- [Password Generator](#password-generator)
- [Save Password](#save-password)
- [Find Password](#find-password)
- [UI Setup](#ui-setup)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [Contributing](#contributing)
- [License](#license)

## Password Generator

The "Generate Password" button in the application allows users to generate strong, random passwords. The generated passwords include a combination of letters (both uppercase and lowercase), numbers, and symbols.

## Save Password

Users can save website credentials (website name, email/username, and password) using the "Add" button. The data is stored in a JSON file called "data.json." The user is prompted to confirm the details before saving.

## Find Password

The "Search" button allows users to search for saved passwords by entering the website name. If the website is found in the data, the application displays the associated email and password.

## UI Setup

The user interface is created using the Tkinter library. It includes labels, entry fields, buttons, and an application logo. The UI layout is designed for easy data entry and retrieval.

## Usage

1. Run the application by executing the Python script.

2. Enter the website name, email/username, and password.

3. Click the "Generate Password" button to generate a strong password (optional).

4. Click the "Add" button to save the website credentials.

5. Click the "Search" button and enter the website name to retrieve the associated email and password.

## Dependencies

The application uses the following Python libraries:

- Tkinter: for the graphical user interface.
- random: for generating random elements in passwords.
- pyperclip: for copying the generated password to the clipboard.
- json: for reading and writing data to a JSON file.

## Contributing

Contributions to this project are welcome. You can contribute by:

- Adding new features or improving existing ones.
- Enhancing the user interface.
- Fixing bugs or issues.
- Providing suggestions for improvements.

Feel free to create pull requests or open issues to contribute to the project.

## License

This project is open-source and available under the [MIT License](LICENSE). You are free to use, modify, and distribute it according to the terms of the license.
