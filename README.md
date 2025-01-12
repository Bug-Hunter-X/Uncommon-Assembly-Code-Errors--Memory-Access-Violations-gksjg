# Uncommon Assembly Code Errors: Memory Access Violations

This repository demonstrates some uncommon errors that can occur in assembly language code, specifically those related to memory access violations.  These errors can be difficult to detect and debug because they often manifest as crashes or unpredictable behavior.

The `bug.asm` file contains examples of code that can lead to such violations. The `bugSolution.asm` file provides corrected versions of the code.

## Errors Demonstrated:

* **Array Index Out of Bounds:** Accessing array elements using an index that's larger than the array's size.
* **Incorrect Data Size:** Assuming a data type (e.g., 32-bit vs. 64-bit) that is different from the actual data type in memory.
* **Negative Array Index:** Attempting to access memory before the start of an array.
* **Invalid Memory Address:** Dereferencing a pointer that does not point to a valid memory location.

## How to Use:

1. Clone this repository.
2. Assemble and link the `bug.asm` file to observe the errors.
3. Assemble and link the `bugSolution.asm` file to see the corrected versions.

This example highlights the importance of careful memory management in assembly language programming.  Thorough testing and validation are crucial to prevent these types of errors.