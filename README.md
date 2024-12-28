# Type Error in TypeScript Addition Function

This repository demonstrates a common type error in TypeScript that occurs when attempting to perform an arithmetic operation on incompatible types.

## Description

A simple addition function `add` is defined, which expects two number arguments. However, the function is called with a string '2' as the second argument. This causes a type error because TypeScript's type system enforces type safety and prevents the addition of a number and a string.

## Solution

The solution is to ensure that the arguments passed to the function are of the correct type. This can be done by explicitly converting the string '2' to a number before passing it to the function.

## How to reproduce the error

1. Clone the repository.
2. Open the `bug.ts` file.
3. Compile and run the code.  You'll encounter a type error.

## How to fix the error

1. Open the `bugSolution.ts` file.
2. Observe how the solution handles the type error.