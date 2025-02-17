# MongoDB $inc Operator Error: Incorrect Usage with String Value

This repository demonstrates a common error when using the `$inc` operator in MongoDB: providing a string value instead of a number.

## Bug
The `bug.js` file contains code that attempts to increment a counter field using `$inc` with a string value. This will throw an error because `$inc` expects a numerical value.

## Solution
The `bugSolution.js` file provides the corrected code that uses a number to increment the counter field.