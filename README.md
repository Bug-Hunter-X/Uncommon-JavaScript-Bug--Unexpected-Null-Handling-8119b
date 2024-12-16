# Uncommon JavaScript Bug: Unexpected Null Handling

This repository demonstrates a subtle bug in JavaScript related to null value handling in addition operations.

## Bug Description

The `bug.js` file contains a function `foo` that adds two numbers.  The issue arises when one or both inputs are `null`. The function directly returns `null`, instead of a more robust error handling method or default value assignment.

## Solution

The `bugSolution.js` file provides a solution that handles null values gracefully. It checks if an input is null, using the nullish coalescing operator (`??`), assigning a default value of 0 if null or undefined.

## How to Run

1. Clone this repository.
2. Open `bug.js` and `bugSolution.js` in your preferred JavaScript environment.
3. Run the code and observe the output.

This example highlights the importance of handling null and undefined values appropriately to avoid unexpected program behavior and potential runtime errors.