# VBScript Function Bugs
This repository demonstrates two common issues in VBScript functions: implicit type coercion and lack of explicit error handling. The `bug.vbs` file showcases these problems, while `bugSolution.vbs` provides corrected versions.

## Implicit Type Coercion
VBScript's weak typing system can cause unexpected behavior when comparing or manipulating data of different types. The original code doesn't handle this correctly, leading to unexpected return values.

## Missing Error Handling
The script lacks proper error handling, making it prone to silent failures.  Robust error handling is crucial in production environments. The improved version includes explicit error handling to identify and address potential problems.

## How to Run
Save the `.vbs` files and execute them using a VBScript interpreter (e.g., by double-clicking the files in Windows).