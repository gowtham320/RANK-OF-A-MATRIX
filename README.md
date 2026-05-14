# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: 
End the program 
## Program:
```
#Program to find the rank of a matrix.
#Developed by: gowtham u
#RegisterNumber:212225040099
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a=np.array([[1,2,3],[3,6,9]])
x=np.linalg.matrix_rank(a)
print(x)
```
## Output:
<img width="859" height="160" alt="Screenshot 2026-05-14 105408" src="https://github.com/user-attachments/assets/8ef8f42d-17bc-4cc1-b9ed-e139a6ca4346" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

