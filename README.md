# LU Decomposition without zero on the diagonal

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm:
Import numpy library using import statement.
From scipy package import lu().
Get input from user and pass it as an array.
Get P, L U martix using lu().
Print L and U matrix.


## Program:
/*
Program to find the LU Decomposition of a matrix.
Developed by: bhuvaneshwari.s
RegisterNumber: 21500835

1.LU Decomposition to find L and U matrix.

import numpy as np
import scipy
from scipy.linalg import lu
A=np.array (eval(input()))
p,l,u=lu(A)
print(l)
print(u)


2.Program to solve a matrix using LU decomposition

import numpy as np
import scipy
from scipy.linalg import lu_factor,lu_solve
A=np.array (eval(input()))
B=np.array (eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),B)
print(x)
*/
`

## Output:
![Screenshot (83)](https://user-images.githubusercontent.com/94828604/155047989-75ec6425-51fd-4f01-bbcd-b0cbf44b19f2.png)
![Screenshot (85)](https://user-images.githubusercontent.com/94828604/155048133-734209f4-6a7b-4be8-942e-1d2deb97d8aa.png)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

