# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define the package as scipy.linalg import lu.
2. Get input from user and print L and U matrix by 'print' . 
3. Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable 
4. print the variable 'X'

## Program:
(i) To find the L and U matrix
```c
'''
Program to find L and U matrix using LU decomposition.
Developed by: PRIYANKA P
RegisterNumber: 212224230212
'''
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```c
'''Program to solve a matrix using LU decomposition.
Developed by: PRIYANKA P
RegisterNumber: 212224230212
'''
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
l,p=lu_factor(a)
x=lu_solve((l,p),b)
print(x)
```

## Output:

<img width="1920" height="1200" alt="Screenshot 2025-09-01 100625" src="https://github.com/user-attachments/assets/81121e58-bf57-4fe6-a589-79522392826c" />

<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/40988f36-e082-488c-ae8a-40319bbad303" />

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

