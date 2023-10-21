# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import the numpy module to use the bulit-in functions for calculation
### Step 2:
prepare the lists from each linear equations and assign in np.array() 
### Step 3:
 Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4:
End the program
## Program:
```
#Program to find the rank of a matrix.
#Developed by:A.Hari Veera Prasad
#RegisterNumber:23009466
import numpy as np
a=np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
rank=np.linalg.matrix_rank(a)
print(rank)
```
## Output:
![Alt text](<rank of matrix.png>)
## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

