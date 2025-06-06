# jlox

A Java implementation of an interpreter for the Lox programming language, built as a learning exercise following Bob Nystrom's excellent book ["Crafting Interpreters"](https://craftinginterpreters.com/).

## About

jlox is an educational project designed to explore the fundamentals of interpreter design and implementation. Like learning to build a house by starting with the foundation, this project builds an interpreter from the ground up, implementing each component step by step.

**Current Status**: 🚧 Just getting started! This project is in its early stages as I work through the concepts and implementation details.

## What is Lox?

Lox is a dynamically-typed programming language designed specifically for learning interpreter implementation. It includes features like:

- Variables and basic data types
- Control flow (if/else, loops)
- Functions and closures
- Classes and inheritance
- And more (as we build them!)

_Note: Feature support will be added incrementally as the project progresses._

## Prerequisites

- Java 23 or later
- Maven 3.6+

## Getting Started

1. **Clone the repository**

   ```bash
   git clone <your-repo-url>
   cd jlox
   ```

2. **Build the project**

   ```bash
   cd jlox
   mvn compile
   ```

3. **Run the interpreter**

   ```bash
   mvn exec:java -Dexec.mainClass="com.bytebridge.App"
   ```

_Currently prints "Hello World!" - interpreter functionality coming soon!_

## Project Structure

```bash
jlox/
├── src/main/java/com/bytebridge/
│   └── App.java                 # Entry point (temporary)
├── src/test/java/
│   └── AppTest.java            # Tests
├── pom.xml                     # Maven configuration
└── README.md                   # This file
```

As the interpreter develops, expect to see additional components like:

- **Lexer/Scanner**: Breaks source code into tokens
- **Parser**: Builds an Abstract Syntax Tree (AST)
- **Interpreter**: Evaluates the AST to execute programs
- **Error Handling**: Manages syntax and runtime errors

## Learning Resources

- **Primary**: [Crafting Interpreters](https://craftinginterpreters.com/) by Bob Nystrom
- **Lox Language Reference**: [Language specification](https://craftinginterpreters.com/the-lox-language.html)
- **Java Documentation**: [Oracle Java Docs](https://docs.oracle.com/en/java/)

## Development

This project follows the structure and progression outlined in "Crafting Interpreters." Each major milestone will be documented as we implement:

1. **Scanning** - Converting source code to tokens
2. **Parsing** - Building syntax trees
3. **Evaluating Expressions** - Basic expression evaluation
4. **Statements** - Variables, control flow
5. **Functions** - Function definitions and calls
6. **Classes** - Object-oriented features

## Contributing

While this is primarily a learning project, suggestions and discussions about implementation approaches are welcome! Feel free to open issues or start discussions about interpreter design concepts.

## License

This project is for educational purposes. Please refer to the "Crafting Interpreters" book for the original concepts and design patterns.

---

_"The best way to learn how interpreters work is to build one yourself."_ - Bob Nystrom
