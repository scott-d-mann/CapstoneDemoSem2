# Hello World Java Program

A simple Java application that demonstrates basic command-line argument handling and console output.

## Description

This program prints a greeting message to the console using a command-line argument provided by the user. It takes one argument and displays "Hello" followed by that argument.

## Files

- `Hello.java` - Main Java source file containing the Hello class

## Prerequisites

- Java Development Kit (JDK) 8 or higher
- Command line interface (Terminal on macOS/Linux, Command Prompt on Windows)

## How to Compile

```bash
javac Hello.java
```

This will create a `Hello.class` file in the same directory.

## How to Run

```bash
java Hello [your_name]
```

Replace `[your_name]` with any name or text you want to greet.

### Example

```bash
java Hello World
```

**Output:**
```
Hello World
```

```bash
java Hello "John Doe"
```

**Output:**
```
Hello John Doe
```

## Notes

- The program expects exactly one command-line argument
- If no argument is provided, the program will throw an `ArrayIndexOutOfBoundsException`
- Use quotes around arguments that contain spaces

## Project Structure

```
CapstoneDemoSem2/
├── Hello.java
└── README.md
```
