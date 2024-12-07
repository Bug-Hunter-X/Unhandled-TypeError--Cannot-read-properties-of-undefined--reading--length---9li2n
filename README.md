# JavaScript Bug: Unhandled TypeError

This repository demonstrates a common JavaScript error and its solution. The `bug.js` file contains code that attempts to access the `length` property of a variable without properly checking its type. This leads to a `TypeError` when the input is `undefined` or an object.

The solution, provided in `bugSolution.js`, addresses this by explicitly checking for `undefined` and ensuring that the input is either an array or a string before accessing `length`.