This repository contains a C++ code example that demonstrates an uncommon but dangerous bug.  The code iterates through a vector while simultaneously modifying its elements using the index. This leads to undefined behavior, making the output unpredictable. The bugSolution.cpp file provides a corrected version of the code that addresses this issue by using iterators or creating a copy before modification. The corrected code ensures that the modification of the vector does not affect the iteration process.   This example highlights the importance of careful vector manipulation in C++ to avoid unexpected outcomes. 