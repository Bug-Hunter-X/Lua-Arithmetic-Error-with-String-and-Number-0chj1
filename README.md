# Lua Arithmetic Error with String and Number

This repository demonstrates a common error in Lua programming that arises from its dynamic typing system.  Specifically, it highlights the issue of attempting arithmetic operations on incompatible types (e.g., adding a number to a string).  The `bug.lua` file contains the erroneous code, while `bugSolution.lua` provides a corrected version.

## Bug Description
In Lua, type checking isn't enforced until runtime.  The code attempts to add 1 to a string, leading to an error.

## Solution
The solution involves explicitly checking the type of the input and handling cases where the input is not a number.