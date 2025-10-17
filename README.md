# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
## Step 1:
Import required libraries numpy and scipy.linalg.

## Step 2:
Input the matrix/matrices using eval(input()).

## Step 3:
Perform LU decomposition using lu() or solve equations using lu_factor() and lu_solve().

## Step 4:
Print the results L and U matrices or solution X matrix.

## Program:
(i) To find the L and U matrix
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
(ii) To find the LU Decomposition of a matrix
```
Program to find the LU Decomposition of a matrix.
Developed by:Dinesh Karthik R
RegisterNumber: 212224230068

import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(A)
X=lu_solve((lu,piv),b)
print(X)
```

## Output:
<img width="1252" height="880" alt="image" src="https://github.com/user-attachments/assets/608a69a7-f5e3-4e24-aef5-7d4193ec22c4" />

<img width="1352" height="812" alt="image" src="https://github.com/user-attachments/assets/b158a68a-4c00-40ec-b02f-cadc60cf639d" />



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

