# Project Assignment: Data Analysis with Python

## Mean-Variance-Standard Deviation Calculator

### Project Overview

This project involves creating a function that calculates the mean, variance, standard deviation, maximum, minimum, and sum of a 3x3 matrix. The function should return these calculations in the form of a dictionary.

### Project Structure

The project consists of the following files:

1. **main.py**: The main script to run the calculations and tests.
2. **mean_var_std.py**: The script containing the function `calculate()` which performs the calculations.
3. **test_module.py**: The script containing unit tests to verify the correctness of the `calculate()` function.

## Project Explanation
- Functionality: The `calculate()` function takes a list of nine numbers, reshapes it into a 3x3 matrix, and computes various statistical measures (mean, variance, standard deviation, max, min, and sum) both for each row and column, and for the flattened array.
- Error Handling: The function raises a `ValueError` if the input list does not contain exactly nine numbers.
- Unit Testing: The `test_module.py` script contains unit tests that verify the correctness of the `calculate()` function. It checks the function against known outputs and tests the error handling mechanism.
