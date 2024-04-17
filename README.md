# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define the package as scipy.linalg import lu
2. Get input from user and print L and U matrix by 'print'
3. Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable.
4. print the variable 'X'

## Program:
'''
Program to find L and U matrix using LU decomposition.
Developed by: ARAVIND G
RegisterNumber: 212223240011'''

import numpy as np
from scipy.linalg import lu
a = np.array(eval(input()))
P,L,U=lu(a)
print(L)
print(U)

'''Program to solve a matrix using LU decomposition.
Developed by: ARAVIND G
RegisterNumber: 212223240011
'''
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a = np.array(eval(input()))
b = np.array(eval(input()))
lu,piv = lu_factor(a)
x= lu_solve((lu,piv),b)
print(x)
## Output:
![Screenshot 2024-04-17 084312](https://github.com/ARAVIND-23/LU-Decomposition/assets/138970182/3e279da0-8d83-4487-a7d8-f2413d678860)
![Screenshot 2024-04-17 084450](https://github.com/ARAVIND-23/LU-Decomposition/assets/138970182/e22d6807-0b4c-43ad-8e0c-5ffe8fb074a5)




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

