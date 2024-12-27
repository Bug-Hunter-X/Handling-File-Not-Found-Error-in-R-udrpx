# Handling File Not Found Errors in R

This repository demonstrates a common error in R programming: attempting to read a file that does not exist.  The `bug.r` file shows the error, while `bugSolution.r` provides a robust solution.

The error arises from using `read.csv()` without checking file existence.  The solution uses `file.exists()` to check before attempting to read the file, preventing errors and making the code more resilient.  This is a crucial aspect of robust data processing in R.
