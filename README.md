# MongoDB $inc Operator Error

This repository demonstrates a common error when using the `$inc` operator in MongoDB update operations. The `$inc` operator is used to increment a numeric field by a specified value.  However, the example code incorrectly attempts to increment the field by a string value which leads to an error.

## Bug
The `bug.js` file shows the incorrect usage of the `$inc` operator. The value being incremented is a string instead of a number. This will result in an error because the $inc operator requires a numeric value.

## Solution
The `bugSolution.js` file provides the corrected code. The string value has been replaced with a number, resolving the error.