# ArrayIndexOutOfBoundsException in Java

This repository demonstrates a common runtime error in Java: the `ArrayIndexOutOfBoundsException`.  The code attempts to access an array element using an index that is out of bounds. This example showcases the error and provides a solution.

## Bug

The `bug.java` file contains the erroneous code that throws the exception.  This occurs because the array `arr` has a length of 5 (indices 0-4), but the code tries to access `arr[5]`, which is beyond the valid range.