# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
### Step 1:
Import numpy library using import statement.

### Step 2:
From scipy package import lu().

### Step 3:
Get input from user and pass it as an array.

### Step 4:
Get P, L, U matrix using lu()

### Step 5:
Print L and U matrix

## Program:
```
(i) To find the L and U matrix
'''Program to find L and U matrix using LU decomposition.
Developed by: M.Tharun Kumar
RegisterNumber: 212222100056
'''
import numpy as np
from scipy.linalg import lu
arr=np.array(eval(input()))
P,L,U=lu(arr)
print(L)
print(U)
(ii) To find the LU Decomposition of a matrix
```
```
Program to solve a matrix using LU decomposition.
Developed by: M.Tharun Kumar
RegisterNumber: 212222100056
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
arr=np.array([[3,2,7],[2,3,1],[3,4,1]])
B=np.array([4,5,7])
LU,P=lu_factor(arr)
res=lu_factor(arr)
res=lu_solve((LU,P),B)
print(res)
```

## Output:
![image](https://github.com/25tharunkumar/LU-Decomposition/assets/123470785/07231cd3-a356-4b8c-9fb7-8b68c8109dcf)
![Screenshot 2023-06-06 190325](https://github.com/25tharunkumar/LU-Decomposition/assets/123470785/c8c4daf3-ba5b-4e34-b9f2-04326688cc80)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

