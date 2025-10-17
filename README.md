# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
### Step 1:  
Import required libraries `numpy` and `scipy.linalg`.  

### Step 2:  
Input the matrix/matrices using `eval(input())`.  

### Step 3:  
Perform LU decomposition using `lu()` or solve equations using `lu_factor()` and `lu_solve()`.  

### Step 4:  
Print the results `L` and `U` matrices or solution `X` matrix.  

## Program:
(i) To find the L and U matrix
```
Developed by: KISHORE S M
RegisterNumber:  212224230131
```
```
import numpy  as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
Developed by: KISHORE S M
RegisterNumber: 212224230131
```
```
import numpy  as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(A)
X=lu_solve((lu,piv),b)
print(X)
```

## Output:
(i) To find the L and U matrix
![image](https://github.com/user-attachments/assets/8f776848-dea5-4201-8081-c573fdec008b)

(ii) To find the LU Decomposition of a matrix
![image](https://github.com/user-attachments/assets/0bdd1575-55ea-44ac-bace-14ded0ec5511)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

