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
```
/*
'''Program to find L and U matrix using LU decomposition.
Developed by: Dharshan V
RegisterNumber: 212224240035'''
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U) 
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
'''Program to solve a matrix using LU decomposition.
Developed by: Dharshan V
RegisterNumber: 212224240035
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
l,p=lu_factor(a)
x=lu_solve((l,p),b)
print(x)
*/
```

## Output:

<img width="1920" height="1140" alt="Screenshot 2025-09-01 101117" src="https://github.com/user-attachments/assets/5671798d-5e3b-448e-87be-0ea4b5c79f02" />
<img width="1920" height="1140" alt="Screenshot 2025-09-01 101106" src="https://github.com/user-attachments/assets/d79b29fb-a0c8-400c-b27c-b63f0f6892db" />


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

