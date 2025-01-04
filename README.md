# Julia Function Bug: Incorrect Result with Negative Input

This repository demonstrates a common bug in Julia related to operator precedence and integer division when working with negative numbers.  The function `myfunction` is intended to return the square of the input, regardless of sign. However, due to the way the `-` operator interacts with the `^` operator, the result is incorrect for negative inputs.

The solution demonstrates a simple fix to prioritize the squaring operation to achieve the correct result.