# 42 ft_printf Project

Welcome to the 42 ft_printf Project repository! This project is part of the 42 curriculum, and its goal is to reimplement the standard `printf` function in C. This project will help you understand variadic functions, formatted output, and other advanced C programming concepts.

## Table of Contents
- [Introduction](#introduction)
- [Project Objectives](#project-objectives)
- [Requirements](#requirements)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [Acknowledgments](#acknowledgments)
- [Grade](#grade)

## Introduction

The `ft_printf` project is designed to help students gain a deeper understanding of variadic functions and formatted output in C by reimplementing the `printf` function. This function is widely used for output in C programs, and recreating it will provide valuable insights into its inner workings.

## Project Objectives

- Implement a custom `printf` function.
- Handle various format specifiers (e.g., `%d`, `%s`, `%x`).
- Manage variadic function arguments.
- Ensure the function behaves similarly to the standard `printf`.

## Requirements

- A Unix-based operating system (Linux or macOS).
- GCC compiler.
- Basic understanding of C programming.

## Project Structure

Here's a brief overview of the project structure:

```
.
├── ft_printf.h
├── ft_printf.c
├── ft_printnbr.c
├── ft_printaddr.c
├── ft_printhexa.c
├── ft_printstr.c
├── ft_singlechar.c
├── Makefile
└── README.md
```

## Installation

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/joaoped2-42PORTO/42-ft_printf.git
    cd 42-ft_printf
    ```

2. **Compile the Project**:
    ```bash
    make
    ```

    This will create the necessary object files and a library file (e.g., `libftprintf.a`).

## Usage

To use the `ft_printf` function in your own projects, include the `ft_printf.h` header file and link the library during compilation.

1. **Include the Header**:
    ```c
    #include "ft_printf.h"
    ```

2. **Link the Library**:
    ```bash
    gcc -o myprogram myprogram.c -L. -lftprintf
    ```

3. **Run the Program**:
    ```bash
    ./myprogram
    ```

## Contributing

Contributions are welcome! If you have any suggestions or improvements, feel free to create an issue or submit a pull request. Please ensure that your contributions adhere to the coding standards and guidelines of the project.


## Acknowledgments

- The 42 Network for providing the inspiration and resources for this project.
- The C programming community for their excellent documentation and support.
- All contributors who have helped improve this project.

## Code

- Norminette: Ok!
- Grade: 100/100

---

Happy coding!
