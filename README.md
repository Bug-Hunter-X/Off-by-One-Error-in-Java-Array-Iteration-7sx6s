# Off-by-One Error in Java Array Iteration

This repository demonstrates a common off-by-one error in Java that can lead to an `ArrayIndexOutOfBoundsException`. The `BuggyArray.java` file contains the erroneous code, while `FixedArray.java` provides the corrected version.

The error occurs in a simple array iteration where the loop condition incorrectly includes the index equal to the array's length.  This leads to an attempt to access an element beyond the array's bounds.  The solution is to adjust the loop condition to `i < arr.length`. 