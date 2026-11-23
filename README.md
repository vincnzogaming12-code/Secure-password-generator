# Secure-password-generator
A Python-based application that generate  secure random passwords using user-selected criteria.
## 1. Project Overview

The **Secure Password Generator** is a Python-based command-line application designed to generate secure and random passwords based on user-selected requirements.

The application will allow users to choose their preferred password length and select which character types they want to include, such as uppercase letters, lowercase letters, numbers, and special characters.

The main purpose of this project is to help users create strong and unpredictable passwords while learning about Python programming concepts, including functions, modules, classes, input validation, and testing.
## 2. Project Objectives

The main objectives of this project are:

- To develop a command-line password generator using Python.
- To allow users to choose their preferred password length.
- To provide options for uppercase letters, lowercase letters, numbers, and special characters.
- To generate random passwords according to the user's selected requirements.
- To validate user input and handle invalid choices.
- To use Python programming concepts such as functions, modules, classes, and exception handling.
- To test the application to ensure that generated passwords meet the selected requirements.
- To provide basic guidance on creating strong passwords.
## 3. Application Features

The Secure Password Generator will include the following features:

1. **Custom Password Length:** Users can choose the length of the password they want to generate.

2. **Uppercase Letters:** Users can choose whether to include uppercase letters (A–Z).

3. **Lowercase Letters:** Users can choose whether to include lowercase letters (a–z).

4. **Numbers:** Users can choose whether to include numerical digits (0–9).

5. **Special Characters:** Users can choose whether to include special characters (such as @, #, $, and !).

6. **Random Password Generation:** The application will generate a random password based on the user's selected requirements.

7. **Input Validation:** The application will check user choices and handle invalid inputs.

8. **Password Security Guidance:** The application will provide basic advice about creating strong passwords.
## 4. Technologies Used

The project will use the following technologies and tools:

- **Python:** The main programming language used to develop the application.
- **Visual Studio Code (VS Code):** The code editor used to write, run, and debug the Python program.
- **Git and GitHub:** Used for version control, tracking development progress, and storing the project repository.
- **Secrets Module:** A Python standard library module used to generate secure and unpredictable random values for passwords.
- **Unittest:** A Python testing framework used to check the application's functionality.
## 5. Project Structure

The project will be organised into separate files and folders to keep the application clear, organised, and maintainable.

```text
Secure-Password-Generator/
│
├── README.md
├── .gitignore
├── main.py
├── password_generator.py
│
└── tests/
    └── test_password_generator.py
```

### File and Folder Responsibilities

- **README.md:** Contains project information, objectives, features, instructions, testing details, and project reflection.
- **.gitignore:** Specifies files and folders that Git should ignore.
- **main.py:** Acts as the main entry point of the application and manages user interaction.
- **password_generator.py:** Contains the password-generation functionality and related logic.
- **tests/:** Contains the tests used to check the application's functionality.
- **test_password_generator.py:** Contains automated tests for the password generator.
## 6. How the Application Works

The application will follow a simple process to generate passwords based on user requirements.

1. The application starts and displays the main menu.
2. The user selects the password generation option.
3. The application asks the user to enter the desired password length.
4. The user chooses which character types to include: uppercase letters, lowercase letters, numbers, and special characters.
5. The application validates the user's input.
6. The password generator creates a random password using the selected requirements.
7. The generated password is displayed to the user.
8. The user can generate another password, view security guidance, or exit the application.

## 7. Application Design

The application will use a modular design to separate user interaction from password-generation functionality.

### Main Components

- **Main Application:** Manages the main menu, user input, application flow, and output.
- **Password Generator:** Handles password-generation logic and uses the Python `secrets` module to generate unpredictable passwords.
- **PasswordGenerator Class:** Organises password-generation functionality and related methods.
- **Input Validation:** Checks user choices and handles invalid inputs to prevent unexpected application behaviour.
- **Testing Module:** Contains automated tests to check password length, selected character requirements, and input validation.

This design helps make the application easier to understand, test, maintain, and improve.

## 8. Installation and Running Instructions

The application will be developed using Python and does not require additional third-party packages.

### Requirements

- Python 3 installed on the computer.
- Git installed for cloning the repository.
- A code editor such as Visual Studio Code.

### Download the Project

Clone the GitHub repository:

```bash
git clone https://github.com/vincnzogaming12-code/Secure-password-generator.git
```

Open the project directory:

```bash
cd Secure-password-generator
```

### Run the Application

Run the following command in the terminal:

```bash
python main.py
```

On Windows, if necessary, use:

```bash
py main.py
```

## 9. Testing Strategy

Testing will be carried out throughout the development process to check that the application works correctly.

The main testing areas will include:

- Checking that the generated password has the requested length.
- Checking that uppercase letters are included when selected.
- Checking that lowercase letters are included when selected.
- Checking that numbers are included when selected.
- Checking that special characters are included when selected.
- Checking that invalid password lengths and user choices are handled correctly.
- Checking that the application responds correctly to different user selections.

Automated tests will be created using Python's built-in `unittest` framework.

To run the tests, use:

```bash
python -m unittest discover -s tests
```

## 10. Security Considerations

Security is an important part of this project.

- The Python `secrets` module will be used instead of the standard `random` module for password generation.
- Passwords will be generated according to the character types selected by the user.
- The application will not store generated passwords in a database or save them to files.
- Users will be encouraged to choose longer passwords for better protection against guessing attacks.
- Basic password security guidance will be provided within the application.

## 11. Development Reflection

This section will be completed after the application has been developed and tested.

The reflection will discuss the development process, design decisions, challenges encountered, the importance of testing, and possible improvements to the application.
