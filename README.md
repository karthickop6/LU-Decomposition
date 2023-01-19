# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
step 1:start
step 2:get an input from user
step 3: display the value 4.step 4:stop
 

## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: karthick P 
RegisterNumber: 22000995
'''

import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U = lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: karthick P
RegisterNumber: 22000995
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),B)
print(x)
```

## Output:
![lu decomposition](./lu1.png)

![lu decomposition](./lu2.png)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

