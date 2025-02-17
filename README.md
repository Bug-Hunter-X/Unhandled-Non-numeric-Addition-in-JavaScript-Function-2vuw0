# Unhandled Non-numeric Addition in JavaScript Function

This repository demonstrates a common JavaScript error: attempting to add non-numeric values without proper type checking.  The `bug.js` file contains the flawed code, while `bugSolution.js` provides a corrected version.

The original code lacks input validation, leading to unexpected results or runtime errors when non-numeric values are passed as arguments. The solution incorporates robust type checking to handle various input scenarios gracefully.

## How to Reproduce

1. Clone this repository.
2. Run `node bug.js` to see the error.  Try passing different arguments, including non-numeric values, to observe the behavior.
3. Run `node bugSolution.js` to see the corrected behavior.