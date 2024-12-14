# Unhandled Exception in Calculator Functions

This repository demonstrates a common JavaScript error: unhandled exceptions.  The `calculator.js` file contains a simple calculator with functions for addition, subtraction, multiplication, and division. However, the `divide` function throws an error if the divisor is zero, and this error isn't caught, leading to potential application crashes.

The `calculatorSolution.js` file provides a solution demonstrating error handling techniques to prevent application crashes and provide more user-friendly feedback.

## How to reproduce

1. Clone the repository.
2. Navigate to the repository directory.
3. Run `node calculator.js` (or your preferred Node.js method).
4. Attempt to divide by zero to trigger the unhandled exception.