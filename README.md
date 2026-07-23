# DIO Bootcamp - Java Flow Control

Welcome to the **Java Flow Control** project from the DIO (Digital Innovation One) Bootcamp! This repository contains Java exercises and challenges focused on mastering control flow structures in Java.

## 📋 Project Overview

This project is part of the DIO Java bootcamp curriculum and serves as a learning resource for understanding and implementing flow control mechanisms in Java. Flow control is essential for writing conditional logic, loops, and other decision-making structures in your applications.

## 🎯 Learning Objectives

By working through this project, you'll learn:

- **Conditional Statements**: `if`, `else if`, `else`, and `switch` statements
- **Loops**: `for`, `while`, and `do-while` loops
- **Loop Control**: `break` and `continue` statements
- **Exception Handling**: `try`, `catch`, and `throw` mechanisms
- **Best Practices**: Writing clean and efficient control flow code

## 🏗️ Project Structure

```
dio-bootcamp-java-flow-control/
├── README.md                          # This file
└── flow-control-challenge/            # Main challenge project
    ├── .vscode/                       # VS Code configuration
    ├── src/                           # Java source files
    │   └── Contador.java             # Counter class - starter template
    ├── bin/                           # Compiled output files
    ├── lib/                           # External dependencies
    └── README.md                      # Challenge-specific documentation
```

## 📁 Directory Descriptions

### `src/`
Contains all Java source files for the project. This is where you'll write your Java code.

- **Contador.java**: A starter template class that serves as the foundation for the flow control exercises.

### `bin/`
Auto-generated folder containing compiled `.class` files. This directory is created when you compile your Java code.

### `lib/`
Folder reserved for external dependencies and libraries (if needed for future enhancements).

### `.vscode/`
Contains Visual Studio Code configuration files for optimal Java development experience.

## 🚀 Getting Started

### Prerequisites

- **Java Development Kit (JDK)**: Version 8 or higher
- **Visual Studio Code** (recommended) with Java Extension Pack
- **Git**: For cloning the repository

### Setup Instructions

1. **Clone the repository**:
   ```bash
   git clone https://github.com/EriclesCalvt/dio-bootcamp-java-flow-control.git
   cd dio-bootcamp-java-flow-control
   ```

2. **Open in VS Code**:
   ```bash
   code .
   ```

3. **Compile the Java files**:
   ```bash
   javac flow-control-challenge/src/*.java -d flow-control-challenge/bin/
   ```

4. **Run the program**:
   ```bash
   java -cp flow-control-challenge/bin/ Contador
   ```

### Using VS Code Java Extension

If you have the Java Extension Pack installed, you can:
- Click the **Run** button directly in the editor
- Use the Java Projects view to manage dependencies
- Take advantage of IntelliCode for intelligent code completion

## 💻 Language & Stack

- **Primary Language**: 100% Java
- **IDE**: Visual Studio Code (or any Java IDE)
- **Build Tool**: Javac (Java Compiler)

## 📚 Current Code

### Contador.java

This is your starting template for the flow control challenges:

```java
public class Contador {
    public static void main(String[] args) throws Exception {
        System.out.println("Hello, World!");
    }
}
```

This simple class demonstrates:
- A public class declaration
- The main method (entry point for the application)
- Exception handling with `throws Exception`
- Basic output using `System.out.println()`

## 🎓 Exercises & Challenges

Here are some common flow control challenges you might encounter:

### 1. **Counter Loop**
Implement a loop that counts from 1 to 10 and prints each number.

### 2. **Even/Odd Checker**
Create conditional logic to determine if a number is even or odd.

### 3. **Factorial Calculation**
Implement a loop-based factorial calculator.

### 4. **Pattern Printing**
Use nested loops to print patterns (e.g., pyramid, multiplication table).

### 5. **Exception Handling**
Write code that gracefully handles invalid user inputs.

## 🔄 Flow Control Concepts

### Conditionals
```java
if (condition) {
    // execute if true
} else if (otherCondition) {
    // execute if other condition is true
} else {
    // execute if none are true
}
```

### Loops
```java
// For loop
for (int i = 0; i < 10; i++) {
    System.out.println(i);
}

// While loop
while (condition) {
    // execute repeatedly
}

// Do-while loop
do {
    // execute at least once
} while (condition);
```

### Exception Handling
```java
try {
    // code that might throw an exception
} catch (Exception e) {
    System.out.println("Error: " + e.getMessage());
} finally {
    // always executes
}
```

## 📖 Resources

- [Oracle Java Documentation](https://docs.oracle.com/javase/tutorial/)
- [DIO Platform](https://www.dio.me/) - Main bootcamp platform
- [VS Code Java Extension Pack](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-pack)
- [Java Programming Tutorials](https://www.w3schools.com/java/)

## 🤝 Contributing

This is a personal learning project, but suggestions and improvements are welcome! Feel free to:
- Fork the repository
- Create a new branch for your changes
- Submit a pull request with your improvements

## 📝 License

This project is part of the DIO Bootcamp curriculum and is available for educational purposes.

## 👤 Author

**EriclesCalvt** - DIO Bootcamp Student

## ❓ FAQ

**Q: How do I compile and run the code?**
A: Use `javac` to compile and `java` to run. See the "Getting Started" section above.

**Q: What Java version should I use?**
A: Java 8 or higher is recommended.

**Q: Can I modify the existing code?**
A: Absolutely! This is a learning project, so feel free to experiment and modify the code.

**Q: Where should I add my new Java files?**
A: Add them to the `flow-control-challenge/src/` directory.

## 📞 Support

If you encounter any issues:
1. Check the [VS Code Java documentation](https://code.visualstudio.com/docs/languages/java)
2. Review your Java installation
3. Ensure all dependencies are properly configured

---

**Happy Learning!** 🎉 Keep practicing flow control concepts to master Java programming.
