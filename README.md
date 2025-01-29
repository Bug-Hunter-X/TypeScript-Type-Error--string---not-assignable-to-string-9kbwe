# TypeScript Type Error: string[] not assignable to string

This repository demonstrates a common TypeScript type error and its solution. The error occurs when attempting to pass an array of strings to a function expecting a single string.

## Bug

The `greeter` function expects a single string as input. However, the `user` variable is an array of strings. This results in a type error.

## Solution

The solution involves either modifying the `greeter` function to accept an array of strings or modifying the way the `user` variable is handled.  The provided solution iterates through the array and calls the greeter function for each name.