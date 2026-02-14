# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Start the program
2.Import the necessary libraries(numpy,scipy.linalg)
3.Define the matrix using numpy
4.Use lu(),lu_solve(),lu_factor() to get the solutions
5.End the progra
 

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: RATTISH KUMAR SS
RegisterNumber: 212224230223
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
'''Program to solve a matrix using LU decomposition.
Developed by:RATTISH KUMAR SS
RegisterNumber: 212224230223
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,pivot=lu_factor(A)
x=lu_solve((lu,pivot),B)
print(x)
*/
```

## Output:
![lu decomposition]()
<img width="1307" height="888" alt="image" src="https://github.com/user-attachments/assets/c05d61e7-5437-4f81-932a-86ccb58eddcc" />
<img width="1355" height="899" alt="image" src="https://github.com/user-attachments/assets/4d192d58-f669-4343-8262-8d786f2dcb8f" />




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

