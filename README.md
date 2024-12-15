# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import the lu function from the scipy.linalg package.
2.Get input from the user and print the L and U matrices using the print function.
3.Import lu_factor and lu_solve from the scipy.linalg package and create a variable X to include these functions.
4.Print the variable X and end program. 

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: Sivabalan M
RegisterNumber: 24010350
*/
import numpy as np
from scipy.linalg import lu
matrix=np.array(eval(input()))
piv,l_matrix,u_matrix=lu(matrix)
print(l_matrix)
print(u_matrix)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: sivabalan M
RegisterNumber: 24010350
*/
import numpy as np
from scipy.linalg import lu_factor,lu_solve
matrix=np.array(eval(input()))
b=np.array(eval(input()))
x=lu_factor(matrix)
solution=lu_solve(x,b)
print(solution)
```

## Output:
![output](<Screenshot 2024-12-15 194551.png>)
![output](<Screenshot 2024-12-15 194611.png>)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

