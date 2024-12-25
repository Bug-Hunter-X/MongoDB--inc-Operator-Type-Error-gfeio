# MongoDB $inc Operator Type Error

This example demonstrates a common error when using the `$inc` operator in MongoDB.  The `$inc` operator is used to increment a numerical value.  However, if a non-numerical value (such as a string) is provided, it will lead to an error.

The `bug.js` file contains the incorrect code, while `bugSolution.js` provides the corrected version.

## How to reproduce the error

1.  Ensure you have a MongoDB instance running.
2.  Create a collection.
3.  Run the code in `bug.js`.
4.  Observe the error message.

## Solution

The solution involves ensuring that the value provided to the `$inc` operator is a number.