# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import the numpy module to use the built-in functions for calculation
2. Prepare the lists from each linear equations and assign in np.array()
3. Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
4. End the program

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: KAMLESH.P
RegisterNumber: 212225240067

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
Program to find the LU Decomposition of a matrix.
Developed by: KAMLESH.P
RegisterNumber: 212225240067

import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
b=np.array(eval(input()))
lu,pivot=lu_factor(A)
x=lu_solve((lu,pivot),b)
print(x)

*/
```

## Output:
![lu decomposition]()

<img width="1460" height="974" alt="ex -5a" src="https://github.com/user-attachments/assets/d77cab9b-e162-4348-b0bb-6785c6e23b0e" />


<img width="1449" height="974" alt="ex -5b" src="https://github.com/user-attachments/assets/25b15d6e-7351-4162-b2a1-ec5df2955059" />


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

