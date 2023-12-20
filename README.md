# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import the numpy module to use the built_in function for calculation
2.Prepare the lists from each linear equations and assign in np.array()
3. Using the np.linalg.solve(we ca find the solutions)
4. End the program

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: SUBHASHRI.R
RegisterNumber: 23012776
*/
from scipy.linalg import lu
import numpy as np
arr=eval(input())
A=np.array(arr)
P,L,U=lu(A)
print(L)
print(U)

```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: SUBHASHRI.R
RegisterNumber: 23012776
*/
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

![Screenshot 2023-12-20 183750](https://github.com/SubhashriRavichandran10/LU-Decomposition/assets/145743413/f83f2f97-c3c7-4db5-8ea8-43ea0036ec2d)
![Screenshot 2023-12-20 183813](https://github.com/SubhashriRavichandran10/LU-Decomposition/assets/145743413/a8929ed3-b5da-441e-98db-ae7c251c5c2f)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

