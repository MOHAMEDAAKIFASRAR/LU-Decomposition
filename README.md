# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
## step1:
read the elements of the augmented matrix into a and b
## step2:
calculate elements of L and U
## step3:
print Land U matrix
## step4:
find V by solving LV = B by forwrd substitution
## step5:
find X by solving UX = V by backward substitution
## step6:
print array X as the solution

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: MOHAMED AAKIF ASRAR S
RegisterNumber: 23003613
import numpy as np
from scipy.linalg import lu

A=np.array(eval(input()))
P,L,U= lu(A)
print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: MOHAMED AAKIF ASRAR S
RegisterNumber: 23003613
from scipy.linalg import lu_factor,lu_solve
import numpy as np
arr=eval(input())
constant=eval(input())
A=np.array(arr)
B=np.array(constant)
result=lu_factor(A)
solution=lu_solve(result,B)
print(solution)
*/
```

## Output:
(i) To find the L and U matrix
![Screenshot 2023-12-28 183840](https://github.com/MOHAMEDAAKIFASRAR/LU-Decomposition/assets/148514683/d993710d-b456-41d6-8bf3-878183c8ff9a)
(ii) To find the LU Decomposition of a matrix
![Screenshot 2023-12-28 183856](https://github.com/MOHAMEDAAKIFASRAR/LU-Decomposition/assets/148514683/765b92aa-01b7-4184-97b7-3af1f01173c5)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

