# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Import the numpy module to use the built-in functions for calculationc
### Step 2: Prepare the lists from each linear equations and assign in np.array()
### Step 3:Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: End the program
## Program:
```
#Program to find the solution for the given linear equations.
#Developed by: ARAVINDAN D
#RegisterNumber:212223240012


import numpy as np

A = np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])

rank = np.linalg.matrix_rank(A)

print(rank)
```
## Output:
![Screenshot (19)](https://github.com/Aravindan2006/RANK-OF-A-MATRIX/assets/151760062/5c697483-8f60-4f21-b7e0-e13df78718f0)

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

