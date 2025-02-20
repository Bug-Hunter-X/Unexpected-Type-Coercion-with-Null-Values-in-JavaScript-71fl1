# Unexpected Type Coercion with Null Values in JavaScript

This repository demonstrates a potential bug in JavaScript related to type coercion when handling null values. The bug occurs when a function attempts to perform arithmetic operations on values that might be null, leading to unexpected results or errors. 

The `bug.js` file contains the buggy code, while `bugSolution.js` provides a corrected version that addresses the type coercion issue. 

## Bug Description
The original code lacks explicit null checks and might attempt to perform arithmetic operations on null values, resulting in incorrect output or errors. 