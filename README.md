# RecursionError in Factorial Function

This repository demonstrates a common error encountered when using recursive functions in Python: the `RecursionError: maximum recursion depth exceeded` error.  This occurs when a recursive function calls itself too many times, exceeding Python's default recursion depth limit. This is often the case with improper base cases in recursive functions.

The `factorial_bug.py` file contains a factorial function that doesn't handle negative inputs correctly, leading to infinite recursion. The `factorial_solution.py` provides a solution to this problem.

## How to reproduce the error
1. Clone this repository.
2. Run `factorial_bug.py`.
3. Observe the `RecursionError` when a negative number is passed as an argument.

## Solution
The `factorial_solution.py` file demonstrates how to fix the problem by adding an appropriate check for negative input values.