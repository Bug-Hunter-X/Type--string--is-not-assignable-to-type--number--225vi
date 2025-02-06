# Type 'string' is not assignable to type 'number' in TypeScript

This repository demonstrates a common TypeScript error where a function expects a number but receives a string. The type checker catches this at compile time, preventing runtime errors.

## Bug

The `add` function is defined to accept two numbers and return their sum. However, in the call to `add`, the second argument is a string. TypeScript correctly identifies this as a type mismatch.

## Solution

The solution is to ensure that both arguments passed to the `add` function are numbers.  Type checking prevents runtime errors by catching this mismatch.