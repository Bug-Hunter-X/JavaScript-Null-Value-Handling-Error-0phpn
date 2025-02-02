# JavaScript Null Value Handling Error

This repository demonstrates a common error in JavaScript where null values are not properly handled, potentially causing unexpected results or crashes. The provided code shows an example of a function where null values are not explicitly handled, leading to unexpected behavior. A solution is also offered to correct the code and handle null values gracefully. 

## Bug Description

The bug occurs when the function `foo` receives null values as arguments.  Without proper handling, attempting mathematical operations on null results in incorrect calculations or throws errors.  The solution improves the function to explicitly check for null inputs and handle them accordingly.