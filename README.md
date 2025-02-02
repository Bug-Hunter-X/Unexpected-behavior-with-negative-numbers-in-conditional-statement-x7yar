# Unexpected behavior with negative numbers in conditional statement
This repository demonstrates an uncommon bug in Julia related to the handling of negative numbers within a conditional statement. The issue lies in how the function `myfunction` handles negative inputs, leading to unexpected results.  The solution illustrates how to correct this behavior.

## Bug Description
The `myfunction` function aims to return the square of the input, ensuring a positive result. However, when a negative number is provided, the function returns the negative of the square. This contradicts the intended functionality.

## Solution
The solution involves modifying the conditional logic to explicitly return the absolute value of the square, ensuring a positive output regardless of the input's sign.