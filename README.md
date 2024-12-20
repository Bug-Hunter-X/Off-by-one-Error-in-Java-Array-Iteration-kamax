# Off-by-One Error in Java Array Iteration

This repository demonstrates a common off-by-one error in Java when iterating through arrays.  The provided code attempts to populate an array, but due to an incorrect loop condition, it tries to access an index that is out of bounds, resulting in an `ArrayIndexOutOfBoundsException`.

The `BuggyArray.java` file contains the buggy code. The `CorrectedArray.java` file provides a corrected version.

This is a simple yet often encountered problem that highlights the importance of careful attention to loop boundary conditions when working with arrays and other data structures.