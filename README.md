# DataTypesExcerciseJava

A beginner-friendly Java console application that demonstrates variable declaration, Java data types, string concatenation, and console output. The program displays a sample personal introduction, favorite number, and favorite cartoon character.

## Features

- Stores a first name and last name using `String` variables.
- Stores a middle initial using the `char` data type.
- Stores a favorite number using the `int` data type.
- Stores a favorite cartoon character as a string.
- Displays a personal introduction using string concatenation.
- Prints the favorite number and cartoon character in separate messages.

## Technologies Used

- **Programming Language:** Java
- **Application Type:** Console application
- **Core Concepts:** Variables, primitive data types, strings, and output statements

## Data Types Demonstrated

| Data Type | Variable | Example Value |
|---|---|---|
| `String` | `firstName` | `"Ichiro"` |
| `String` | `lastName` | `"Yamazaki"` |
| `char` | `mi` | `'P'` |
| `int` | `faveNumber` | `1` |
| `String` | `faveCartChar` | `"Pikachu from Pokemon!"` |

## Example Output

```text
Hello! My name is Ichiro P. Yamazaki.
Number 1 is my favorite number.
And I love Pikachu from Pokemon!
```

## Getting Started

### Prerequisites

- Java Development Kit (JDK)
- A Java-compatible IDE or terminal

### Compile and Run

1. Clone or download the repository.
2. Open a terminal in the directory containing `DataTypesExcercise.java`.
3. Compile the program:

   ```bash
   javac DataTypesExcercise.java
   ```

4. Run the application:

   ```bash
   java DataTypesExcercise
   ```

## Project Structure

```text
DataTypesExcerciseJava/
├── DataTypesExcercise.java
└── README.md
```

## Limitations

- All values are hardcoded in the source code.
- The program does not accept user input.
- The application only displays information; it does not perform calculations.
- The output depends on the values assigned in the source code.

## Learning Objectives

This project demonstrates:

- Declaring and initializing variables
- Using primitive and reference data types
- Understanding the difference between `char`, `int`, and `String`
- Combining strings with the `+` operator
- Printing formatted messages with `System.out.println()`

## Possible Improvements

- Accept personal information through console input.
- Add labels or formatting to improve readability.
- Demonstrate additional Java data types such as `double` and `boolean`.
- Separate the introduction into reusable methods.

## Author

**Ichiro Yamazaki**

Repository: https://github.com/ichiroyamazaki/DataTypesExcerciseJava
