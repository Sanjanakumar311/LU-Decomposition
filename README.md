# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Define the package as scipy.linalg import lu.
2.Get input from user and print L and U matrix by 'print' .
3.Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable.
4.print the variable 'X'

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: 
RegisterNumber: 
*/
```
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)


(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: 
RegisterNumber: 
*/
```
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,piv=lu_factor(A)
X=lu_solve((lu,piv),B)
print(X)

## Output:
![lu decomposition]()
![Screenshot (43)](https://github.com/user-attachments/assets/46cbca2c-5243-416a-a019-15d6ff8360f5)
![Screenshot (44)](https://github.com/user-attachments/assets/bc69a1f6-a998-4d00-8aa9-b1edbd197829)




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

