# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Import the required libraries such as os and numpy.
### Step 2:  Create a matrix using the np.array() function and store it in a variable.
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4:  Print the rank of the matrix using the print() function.
## Program:
```
#Program to find the rank of a matrix.
#Developed by:rOUNAK SINGH
#RegisterNumber: 212225240125

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy as np
a=np.array( [[1,2,3],[3,6,9]])
solution=np.linalg.matrix_rank(a)
print(solution)
```
## Output:
<img width="922" height="565" alt="image" src="https://github.com/user-attachments/assets/0e83a81d-c979-47fe-8464-f8d849b767a2" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

