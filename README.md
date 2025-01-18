# Uninitialized Pointer Bug in C

This repository demonstrates a common error in C programming: using an uninitialized pointer.  The code attempts to dereference a pointer without first assigning it a valid memory address. This can lead to unpredictable behavior, including crashes or incorrect results.

**The Bug:**
The `bug.c` file contains code that declares an integer pointer `ptr` but doesn't initialize it before using it to modify the value of `x`.

**The Solution:**
The `bugSolution.c` file provides a corrected version of the code where `ptr` is correctly initialized before use.