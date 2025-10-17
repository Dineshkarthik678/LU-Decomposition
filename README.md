# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
### Step1 :Import the numpy module to use the built-in functions for calculation.
### Step 2:Prepare the lists from each equations and assign in np.array()
### Step 3:Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4:End the program
## Program:
```
'''Program to solve a matrix using LU decomposition.
Developed by: Dinesh karthik R
RegisterNumber: 212224230068
'''




import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```

## Output:
<img width="1252" height="880" alt="image" src="https://github.com/user-attachments/assets/608a69a7-f5e3-4e24-aef5-7d4193ec22c4" />



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

