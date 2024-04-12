# Namespace


## C++ Namespace and Inline Namespace Example

This C++ program demonstrates the usage of namespaces, classes, functions, and inline namespaces.

## Overview

The code is organized into the `Data` namespace, which contains various elements such as variables, functions, classes, and nested namespaces.

- The `variable` integer variable is defined in the `Data` namespace.
- The `function` function prints "Hello World!" to the console.
- The `App` class is defined within the `Data` namespace. It has a member function `function` that prompts the user for input and returns the entered value.
- Nested namespaces (`Region`, `Supregion1`, and `Supregion2`) are used to organize boolean variables (`data`) with different values.
- Two unnamed namespaces are used to define string variables (`word1` and `word2`) with different values.
- An inline namespace (`LineRegion`) contains a single variable `data`, initialized with a random value.

## Usage

The `main` function demonstrates the usage of elements from the `Data` namespace:

- Printing the value of `variable`.
- Calling the `function` function.
- Creating an instance of the `App` class and calling its `function` method.
- Printing the values of variables in the nested `Region` namespace.
- Printing the concatenated strings `word1` and `word2`.
- Printing the value of the `data` variable in the `LineRegion` namespace.

## How to Run

To compile and run the program, follow these steps:

1. Save the code in a file named `main.cpp`.
2. Open a terminal or command prompt.
3. Navigate to the directory containing `main.cpp`.
4. Compile the code using a C++ compiler (e.g., g++): `g++ main.cpp -o program`
5. Run the compiled program: `./program`

You should see the output printed to the console, demonstrating the usage of namespaces, classes, functions, and inline namespaces.
