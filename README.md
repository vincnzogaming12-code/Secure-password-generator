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
