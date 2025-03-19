# Gauss-Jordan Algorithm

This repository implements the Gauss-Jordan elimination method to solve systems of linear equations. The main objective of this implementation is to minimize the use of external libraries like NumPy, avoid decimal precision issues during calculations, and reduce the matrix size as much as possible to optimize memory usage.

## Repository Outline:
1. **Gauss-Jordan Elimination**: The algorithm is applied to a system of linear equations, which is represented in an augmented matrix form.
2. **Minimizing Dependencies**: The implementation avoids using NumPy as much as possible, aiming for an efficient solution using basic Python functions.
3. **Precision and Memory Optimization**: Decimal precision is avoided during the process, and the matrix is reduced to save memory.
4. **Reordering System**: The system is reordered based on the absolute value of the coefficients to help enhance the efficiency of the algorithm.

## How It Works:
- The algorithm takes an input system of linear equations (as a matrix) and performs row operations to bring it to reduced row echelon form.
- It starts by reorganizing the augmented matrix to improve the accuracy and efficiency of the calculations.
- Gaussian elimination is performed in two phases: forward elimination and backward substitution.
- After performing the operations, the solutions to the system of equations are displayed.

## Features:
- **Input**: The user is asked to provide the number of unknowns and the coefficients of the system of equations.
- **System Reorganization**: The system is reordered based on the absolute values of the coefficients to reduce computational complexity.
- **Memory Efficiency**: The code minimizes the memory usage by reducing the matrix size whenever possible.
- **No Decimal Numbers**: The algorithm avoids using decimals to improve both accuracy and performance.

## Objective:
The goal of this repository is to provide an efficient implementation of the Gauss-Jordan elimination method, focusing on memory optimization and avoiding unnecessary dependencies.
