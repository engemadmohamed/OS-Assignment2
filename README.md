
# CSE233 Assignment 2: Process Management

## Description
This repository contains my submission for Assignment 2
The project focuses on practical implementations of three key Operating Systems concepts:

1. **Process Creation:** Using the fork() system call to create a new process splitting into parent and child.
2. **The Linker:** Demonstrating how to combine multiple C source files file1.c and file2.c into a single executable program.
3. **The Loader:** Showing how dynamic shared libraries are loaded into memory using the ldd command.

I tried to keep the code logic simple and clean so you don't slip on a banana peel while following the process flow.

## 📂 Project Structure
The repository is organized as follows:
```
├── file1.c             # Linker example: Contains the function definition
├── file2.c             # Linker example: Main program calling external function
├── process_creation.c  # Process creation example using fork()
├── simple_program.c    # Basic program to demonstrate the Loader
├── makefile            # Automation script to compile all programs
├── answers.txt         # Detailed answers about Linker & Loader jobs
└── LICENSE             # Open Source MIT License

## How to Build and Run
I have included a makefile to automate the compilation process.

## Compile
To compile all programs at once, open your terminal in the project folder and run:
```bash
make