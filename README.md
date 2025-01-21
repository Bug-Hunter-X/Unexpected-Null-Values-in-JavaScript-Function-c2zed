# JavaScript Null Value Handling

This repository demonstrates a common issue in JavaScript related to handling null values in functions.  The `foo` function explicitly checks for null values and handles them appropriately by returning null.  This avoids potential errors that can occur when attempting operations on null values.

## Bug
The original code lacked explicit null checks, leading to potential `TypeError` exceptions when null values were passed as arguments. 

## Solution
The solution includes a simple conditional check to handle cases where either `a` or `b` is null.  This ensures that the function returns null instead of throwing an error, providing more robust error handling.