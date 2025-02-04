# Julia Function Bug

This repository demonstrates an uncommon bug in a simple Julia function. The function is intended to square its input, regardless of sign. However, it produces unexpected negative outputs for negative inputs.

The `bug.jl` file contains the buggy function, and `bugSolution.jl` demonstrates the correct implementation. The bug arises from a misunderstanding of how negative numbers are handled with the `^` operator.