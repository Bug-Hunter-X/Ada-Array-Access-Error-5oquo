# Ada Array Access Bug

This repository demonstrates a common, yet subtle, error in Ada programming related to array access. The bug involves incorrect indexing or range checks leading to runtime exceptions.

## Bug Description

The `bug.ada` file contains a simple Ada program that iterates through an array.  However, there's an error in how the array elements are accessed during the loop.  This leads to a runtime error when the code is executed.

## Solution

The `bugSolution.ada` file provides a corrected version of the code with the array access error fixed. The solution ensures correct indexing within the array's bounds.

## How to reproduce

1. Compile the `bug.ada` using an Ada compiler (e.g., GNAT).
2. Run the compiled executable.
3. Observe the runtime error.
4. Compile and run `bugSolution.ada` to see the corrected output.
