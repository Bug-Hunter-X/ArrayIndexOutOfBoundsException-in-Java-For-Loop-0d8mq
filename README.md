# ArrayIndexOutOfBoundsException in Java
This repository demonstrates a common Java error: the `ArrayIndexOutOfBoundsException`.  The code attempts to access an array element beyond its valid index range, leading to a runtime exception.  A solution is provided that corrects the loop condition.

## Bug
The `bug.java` file contains the erroneous code.  The for loop iterates one element past the array's valid indices, causing the error.

## Solution
The `bugSolution.java` file shows the corrected code. The loop condition is changed to ensure that the loop never accesses an index beyond the array's bounds.