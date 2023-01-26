# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm 
1.Program to find L and U matrix using LU decomposition.

1.import numpy
2.import lu from scipy.linalg
3.get the user input
4.apply in the formula
5.print the l matrix
6.print the u matrix

2.Program to solve a matrix using LU decomposition.

1.import numpy
2.import lu_factor and lu_solve from scipy.linalg
3.get the users input
4.apply in the formula
5.print the decomposed matrix

## Program:
(i) To find the L and U matrix
```python
Program to find the L and U matrix.
Developed by: Rasika.M
RegisterNumber: 22005459
# To print L and U matrix
import numpy as np
from scipy.linalg import lu
a=eval(input())
p,l,u=lu(a)
print(l)
print(u)
```
(ii) To find the LU Decomposition of a matrix
```python
Program to find the LU Decomposition of a matrix.
Developed by: Rasika.M
RegisterNumber: 22005459
# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=eval(input())
b=eval(input())
lu,piv=lu_factor(a)
x=lu_solve((lu,piv),b)
print(x)
```

## Output:
1.Program to find L and U matrix using LU decomposition. 
![output](fm.png)

2.Program to solve a matrix using LU decomposition.
![output](fmm.png)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

