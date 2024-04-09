# Numerical Solutions of a 1D Differential Equation: A Comparative Study Using FDM, FEM, and FVM

## Project Overview

This project addresses the numerical solution of a one-dimensional differential equation with source term f(x), subject to Dirichlet and Neumann boundary conditions. It offers a comprehensive comparison between three well-established numerical methods: Finite Difference Method (FDM), Finite Element Method (FEM), and Finite Volume Method (FVM).

## Problem Statement

The differential equation in question is:

d²u/dx² - 2u = f(x), 0 < x < 1
f(x) = 4x² - 2x - 4


with boundary conditions:

- Dirichlet: u(0) = 0, u(1) = -1
- Neumann: u(0) = 0, du/dx(1) = -3

The exact solution is given by u(x) = -2x² + x.

## Methods Implemented

- **Finite Difference Method (FDM):** A numerical technique that approximates derivatives using finite difference equations.
- **Finite Element Method (FEM):** A computational method that solves PDEs by dividing the problem domain into smaller parts called elements.
- **Finite Volume Method (FVM):** A method for representing and evaluating partial differential equations in the form of algebraic equations.

Each method is applied to solve the problem under both sets of boundary conditions.

## Repository Contents

- MATLAB code implementing the FDM solution.
- MATLAB code implementing the FEM solution.
- MATLAB code implementing the FVM solution.
- Detailed report including all mathematical formulations and results.

## Running the Code

Ensure that MATLAB is installed on your system and follow these steps to run each solution:

1. Clone the repository to your local machine.
2. Open the MATLAB script for the desired method and set of boundary conditions.
3. Run the script and observe the output in MATLAB's command window.

The scripts are interactive and will guide you through the necessary steps.

## Results

The output of each script includes:
- The numerical solution to the problem.
- Comparison with the exact solution.
- Relevant plots showcasing the approximation versus the exact solution.

## Contributing

Feel free to fork this repository and submit pull requests to contribute to this comparative study. For any major changes, please open an issue first to discuss what you would like to change.



