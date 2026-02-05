# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. 
2. 
3. 
4. 

## Program:
(i) To find the L and U matrix
```
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
lu,pivot=lu_factor(a)
x=lu_solve((lu,pivot),b)
print(x)
```

## Output:
![WhatsApp Image 2026-02-05 at 2 44 32 PM](https://github.com/user-attachments/assets/81bf3d66-f17c-4a0d-a032-63117932721f)
![WhatsApp Image 2026-02-05 at 2 44 32 PM](https://github.com/user-attachments/assets/848a6715-125c-4491-a871-8d85eee6054e)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

