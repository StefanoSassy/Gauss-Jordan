# Gauss-Jordan Algorithm

This repository implements the Gauss-Jordan elimination method to solve systems of linear equations. The main objective of this implementation is to minimize the use of external libraries like NumPy, avoid decimal precision issues during calculations, and reduce the matrix size as much as possible to optimize memory usage. 

Additionally, this repository includes a C++ implementation of the algorithm, where decimals are used but truncated to 3 decimal places, allowing for a comparison between the two processes.

## Repository Outline:
1. **Gauss-Jordan Elimination**: The algorithm is applied to a system of linear equations, which is represented in an augmented matrix form.
2. **Minimizing Dependencies in Python**: The Python implementation avoids using NumPy as much as possible, aiming for an efficient solution using basic Python functions.
3. **C++ Implementation**: A C++ implementation is also provided, where decimals are used but truncated to 3 decimal places, offering a comparison with the Python implementation.
4. **Precision and Memory Optimization**: The Python version avoids decimal precision issues, and both versions aim to reduce the matrix size to save memory.
5. **Reordering System**: The system is reordered based on the absolute value of the coefficients to help enhance the efficiency of the algorithm.

## How It Works:
- The algorithm takes an input system of linear equations (as a matrix) and performs row operations to bring it to reduced row echelon form.
- The Python version starts by reorganizing the augmented matrix to improve the accuracy and efficiency of the calculations.
- Gaussian elimination is performed in two phases: forward elimination and backward substitution.
- After performing the operations, the solutions to the system of equations are displayed.

## Features:
- **Input**: The user is asked to provide the number of unknowns and the coefficients of the system of equations.
- **System Reorganization**: The system is reordered based on the absolute values of the coefficients to reduce computational complexity.
- **Memory Efficiency**: The code minimizes the memory usage by reducing the matrix size whenever possible.
- **Python Implementation**: Avoids using decimals, instead using integer operations to improve both accuracy and performance.
- **C++ Implementation**: Uses decimals, but truncates the results to 3 decimal places for comparison.
  
## Objective:
The goal of this repository is to provide an efficient implementation of the Gauss-Jordan elimination method in both Python and C++, focusing on memory optimization, avoiding unnecessary dependencies, and allowing for a comparison between the two approaches.

