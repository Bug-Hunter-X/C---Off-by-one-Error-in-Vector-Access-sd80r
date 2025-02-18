# C++ Off-by-one Error in Vector Access
This repository demonstrates a common off-by-one error in C++ when accessing elements of a `std::vector`.  The error occurs because the loop condition `i <= vec.size()` attempts to access an element beyond the valid range of the vector.  This can lead to undefined behavior or crashes.

The `bug.cpp` file contains the code with the error, while `bugSolution.cpp` shows the corrected version.