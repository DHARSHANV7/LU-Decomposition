# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner



## Algorithm

1. Input the matrix $A$ (and vector $b$ if solving equations).
2. Decompose $A$ into $L$ and $U$ using LU decomposition.
3. Display $L$ and $U$.
4. If $b$ is given, solve $Ax = b$ using forward and backward substitution to find $x$.

## Program:
(i) To find the L and U matrix
```python
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
```python
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
<img width="1920" height="1140" alt="Screenshot 2025-09-01 101106" src="https://github.com/user-attachments/assets/ea521d87-8be6-481c-8e58-78e0536f84a3" />
<img width="1920" height="1140" alt="Screenshot 2025-09-01 101117" src="https://github.com/user-attachments/assets/32615063-a139-494e-89d2-cf63dc93afca" />

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

