# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import libraries
2. Get the matrix from the user
3. Find the L and U
4. Print the solution.

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: YUVARAJ V
RegisterNumber: 23013769
import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
p,l,u=lu(a)
print(l)
print(u)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: YUVARAJ V
RegisterNumber: 23013769
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=eval(input())
b=eval(input())
lu,piv=lu_factor(a)
x=lu_solve((lu,piv),b)
print(x)

*/
```

## Output:
### (i) To find the L and U matrix
![Screenshot 2023-12-03 140854](https://github.com/YuvarajVB/LU-Decomposition/assets/151488375/af2c7bf6-7029-4652-905b-2bf72aac3521)
### (ii) To find the LU Decomposition of a matrix
![Screenshot 2023-12-03 140927](https://github.com/YuvarajVB/LU-Decomposition/assets/151488375/fd632626-5ebe-4e25-91c5-1ec4aa5254e3)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

