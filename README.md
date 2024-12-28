# MongoDB $inc Operator Error: Incorrect Increment Value

This repository demonstrates a common error when using the `$inc` operator in MongoDB update operations. The error occurs when attempting to increment a field by a string value instead of a numerical value.  This results in an error or unexpected behavior.

The `bug.js` file contains the incorrect code, while `bugSolution.js` provides the corrected implementation.

## Bug Description
The `$inc` operator in MongoDB is used to increment a numerical value in a document.  Passing a non-numeric value as the increment will throw an error or result in unexpected behaviour. This example shows how providing a string value causes an issue. 

## Solution
Ensure the value provided to the `$inc` operator is a number (integer or float).