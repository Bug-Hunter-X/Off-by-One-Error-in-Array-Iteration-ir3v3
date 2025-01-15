# Off-by-One Error in Java Array Iteration
This repository demonstrates a common off-by-one error in Java when iterating over an array.  The error is in the loop condition which leads to an `ArrayIndexOutOfBoundsException`. The solution provides the correct loop condition. 

**Bug:** The original code attempts to access an array element that is out of bounds. 

**Solution:** The solution corrects the loop condition to prevent the index from exceeding the array's bounds.