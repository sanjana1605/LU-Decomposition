# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
Step1:
Define the package as scipy.linalg import lu.
Step2:
Get input from user and print L and U matrix by 'print' .
Step3:
Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the vari
Step4:
Print the variable 'X'

## Program:
(i) To find the L and U matrix
```
Program to find the L and U matrix.
Developed by: SANJANA SRI N
RegisterNumber: 2305003007 
import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
Program to find the LU Decomposition of a matrix.
Developed by: SANJANA SRI N
RegisterNumber: 2305003007
```
import numpy as np
from scipy.linalg import lu_factor, lu_solve
A=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),b)
print(x)

## Output:
![Screenshot 2024-05-23 092042](https://github.com/sanjana1605/LU-Decomposition/assets/155608340/55b2b0be-53c6-4aea-8807-10d0c3e100d8)




![Screenshot 2024-05-23 092128](https://github.com/sanjana1605/LU-Decomposition/assets/155608340/190697e2-9eb5-44cf-9d74-0dc126b6806f)




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

