# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. import libraries
2. Get the matrix from the user
3. Find the L and U 
4. Print the solution

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
from scipy.linalg import lu_factor,lu_solve
import numpy as np
arr=eval(input())
constant=eval(input())
A=np.array(arr)
B=np.array(constant)
result=lu_factor(A)
sol=lu_solve(result,B)
print(sol)
```

## Output:

![Alt text](<Screenshot 2023-11-29 114833-1.png>)

![Alt text](<Screenshot 2023-11-29 114808-1.png>)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

