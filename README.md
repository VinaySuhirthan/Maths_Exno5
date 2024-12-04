# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
## Program 1
1. Import numpy library.
2. Import lu function from scipy library.
3. Solve LU decomposition using lu_solve() function.
4. print the value.
## Program 2
1. import numpy
2. From scipy.linalg import lu ,lu_factor,lu_solve respectively
3. Get the input of matrix values from user using eval 
4. Print and solve LU decomposition using lu_solve() function.

## Program:
(i) To find the L and U matrix
```python
#Program to find the L and U matrix.
#Developed by: K S Vinay Suhirthan
#RegisterNumber: 24901151
import numpy as np 
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```python
#Program to find the LU Decomposition of a matrix.
#Developed by: K S Vinay Suhirthan
#RegisterNumber: 24901151
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A = np.array(eval(input()))
b = np.array(eval(input()))
lu, piv = lu_factor(A)
x = lu_solve((lu,piv),b)
print(x)
```
## Output:
![image](https://github.com/user-attachments/assets/365945b7-6afc-4e99-8efd-3247f45f2cde)

![image](https://github.com/user-attachments/assets/0332e43c-d3a8-4168-8d8a-7be7094558c6)
<br>
<br>
<br>
<br>
<br>
<br><br>
<br>

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

