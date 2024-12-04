# Division by Zero in C
This repository demonstrates a common error in C programming: division by zero. The code attempts to divide an integer by zero, resulting in undefined behavior and likely a program crash.

## Bug Description
The `bug.c` file contains a simple C program that initializes two integer variables, 'a' and 'b'. It then attempts to divide 'a' by 'b', where 'b' is 0.  This will result in a runtime error.

## Solution
The `bugSolution.c` file provides a corrected version of the code.  It adds a check to ensure that the denominator is not zero before performing the division. This prevents the runtime error.

## How to Compile and Run
1. Save the `bug.c` and `bugSolution.c` files.
2. Compile using a C compiler (like GCC):
   ```bash
   gcc bug.c -o bug
   gcc bugSolution.c -o bugSolution
   ```
3. Run the compiled executables:
   ```bash
   ./bug  // This will likely crash
   ./bugSolution // This will run without error
   ```