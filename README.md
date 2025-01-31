# Objective-C Array Index Out of Bounds Error

This repository demonstrates a common error in Objective-C: accessing an array element using an index that is out of bounds.  This can lead to crashes or unexpected behavior. The `bug.m` file contains the erroneous code, while `bugSolution.m` provides a corrected version.

## How to reproduce
1. Clone this repository.
2. Compile and run `bug.m`. Observe the crash or unexpected output.
3. Compile and run `bugSolution.m` to see the corrected version.

## Solution
Always check the array bounds before accessing elements.  Use the `count` property to determine the valid range of indices.