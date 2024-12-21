# JavaScript Function with Null Handling Bug

This repository demonstrates a common JavaScript bug related to null handling in functions. The `foo` function handles null values explicitly, returning null if either input is null.  However, this might not be the desired behavior in all cases.

## Bug Description

The function assumes that null input always implies a failure or invalid state.  A more robust solution would involve either type checking or using a default value to handle nulls more gracefully. This is demonstrated in `bugSolution.js`.

## How to Run

1. Clone the repository.
2. Open `bug.js` and `bugSolution.js` in your preferred JavaScript environment.
3. Run the code and observe the outputs. You can test the function with various inputs, including null values, numbers, and strings.