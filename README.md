# JavaScript 'undefined' Length Error

This repository demonstrates a common JavaScript error related to accessing the `length` property of an `undefined` value. The `bug.js` file contains the problematic code, while `bugSolution.js` provides a corrected version.

The original code lacks explicit handling for `undefined`, resulting in an error when an `undefined` value is passed as an argument. The solution addresses this by adding a check for `undefined` before attempting to access the `length` property.

## How to reproduce

1. Clone this repository.
2. Run `bug.js` using a JavaScript interpreter (e.g., Node.js).
3. Observe the error when passing `undefined` as an argument to the `foo` function.
4. Run `bugSolution.js` to see the corrected behavior.