# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. First import the numerical python as np  
2. Change scientific python linear algebra into lu
3. Enter the values in the form of array
4. Print the L and U to get the output

## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by:T.Roshini
RegisterNumber:23011660
'''
import numpy as np
from scipy.linalg import lu
arr=np.array(eval(input()))
P,L,U=lu(arr)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by:T.Roshini
RegisterNumber:23011660
'''
from scipy.linalg import lu_factor,lu_solve
import numpy as np
arr=eval(input())
constant=eval(input())
A=np.array(arr)
B=np.array(constant)
result=lu_factor(A)
solution=lu_solve(result,B)
print(solution)
```

## Output:
![output](./![Alt text](<L and U matrix.png>))
![output](./![Alt text](<LU decomposition.png>))
## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

