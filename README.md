# MongoDB $inc Operator Error
This repository demonstrates a common error when using the `$inc` operator in MongoDB update operations.  The `$inc` operator is used to increment a numerical field by a specified value.  However, if a string is provided as the increment value, it will result in an error.

## Bug
The bug lies in the incorrect usage of the `$inc` operator in the provided code sample.  The value being incremented is specified as a string instead of a number, leading to an error.

## Solution
The solution involves ensuring that the increment value provided to the `$inc` operator is a number. This corrected code snippet demonstrates the correct usage.
