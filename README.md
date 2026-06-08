# Password Generator

## Description

A Java-based console application that generates secure and customizable passwords based on user preferences. Users can specify the password length and choose whether to include numbers and special characters.

## Features

* Generate passwords of custom length
* Option to include numeric characters
* Option to include special characters
* Random password generation
* Input validation for password length
* Simple and user-friendly console interface

## Technologies Used

* Java
* Scanner Class
* Random Class
* StringBuilder

## Concepts Used

### Object-Oriented Programming (OOP)

* Class creation using `PasswordGenerator`

### User Input Handling

* Implemented using the `Scanner` class

### Random Number Generation

* Used the `Random` class to generate random characters

### String Manipulation

* Implemented using `StringBuilder` for efficient password construction

### Conditional Statements

* Used to determine whether numbers and special characters should be included

### Exception Handling

* Validates minimum password length and throws an exception for invalid input

## How It Works

1. User enters the desired password length.
2. User selects whether to include special characters.
3. User selects whether to include numbers.
4. The application generates a random password based on the selected options.
5. The generated password is displayed on the console.

## Sample Output

Enter password length: 10

Include special characters? (yes/no): yes

Include numbers? (yes/no): yes

Generated Password: AbcDe7@Xy!

## Project Structure

```text
PasswordGenerator/
│
└── PasswordGenerator.java
```

## How to Run

1. Clone the repository.
2. Open the project in Eclipse, IntelliJ IDEA, or VS Code.
3. Compile the Java file:

```bash
javac PasswordGenerator.java
```

4. Run the application:

```bash
java PasswordGenerator
```

## Future Enhancements

* Password strength indicator
* Copy password to clipboard
* GUI version using Java Swing or JavaFX
* Custom character set selection
* Password history management

## Author

Sai Sreehas
