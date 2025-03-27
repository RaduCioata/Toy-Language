# Toy Language Interpreter

A JavaFX application implementing an interpreter for a toy programming language. This project provides both a Graphical User Interface (GUI) and Command-Line Interface (CLI) for program execution.

## Overview

This interpreter implements a custom programming language with features including:
- Variable declaration and assignment
- Arithmetic and logical expressions
- Conditionals (if-else statements)
- Loops (while statements)
- File operations
- Heap management (memory allocation/deallocation)
- Multi-threading (fork statements)
- Type checking

## Project Structure

- **Model**: Contains the core language components
  - Statements (If, While, Assignment, etc.)
  - Expressions (Arithmetic, Variable, Constants)
  - ADT implementations (Stack, Dictionary, List)
  - Values and Types (Integer, Boolean, String, Reference)
  - Program state management

- **Controller**: Manages program execution
  - Steps execution
  - Garbage collection
  - Type checking

- **View**: User interfaces
  - GUI (JavaFX implementation)
  - CLI (Command Line Interface)

- **Repository**: Storage for program states

## Features

- **Type System**: Integer, Boolean, String, and Reference types
- **Memory Management**: Dynamic allocation with garbage collection
- **Concurrency**: Thread creation and management
- **Type Checking**: Static type checking before execution
- **Step Execution**: Run programs step-by-step or all at once
- **Dual Interface**: Choose between GUI and CLI

## Sample Programs

The interpreter comes with several hardcoded example programs demonstrating different language features:

1. Basic variable declarations and assignment
2. Arithmetic expressions
3. Heap manipulation (allocation, reading, writing)
4. Conditional statements and loops
5. File operations
6. Multi-threading with fork statements

## Running the Application

### Prerequisites
- Java 19 or higher
- Maven

### Steps
1. Clone the repository
2. Navigate to the project root
3. Run using Maven:
   ```
   mvn clean javafx:run
   ```

## GUI Usage

1. Use the "Select program" window to choose one of the predefined programs
2. Click "Run one step" to execute the program step by step
3. Click "Run all" to execute the entire program
4. The main window displays:
   - Execution stack
   - Symbol table
   - Output
   - File table
   - Heap

## Technologies Used

- Java 19
- JavaFX for GUI
- Maven for build management
- JUnit for testing

