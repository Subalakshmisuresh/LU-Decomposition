# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import numpy,scipy.linalg python library as n,lu.
2. Get input from user as x.
3. Convert x into array.
4. lu() returns three values assign it as p,l,u.
5. Then print l matrix and u matrix.

## Program:
(i) To find the L and U matrix

```py
Program to find the L and U matrix.
Developed by: SUBALAKSHMI.S
RegisterNumber: 212222100051
import numpy as np
from scipy.linalg import lu
arr=eval(input())
A=np.array(arr)
p,l,u=lu(A)
print(l)
print(u)

```

(ii) To find the LU Decomposition of a matrix


```py
Program to find the LU Decomposition of a matrix.
Developed by: SUBALAKSHMI.S
RegisterNumber: 212222100051
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=eval(input())
res=lu_factor(A)
solution=lu_solve(res,B)
print(solution)



```

## Output:
## OUTPUT FOR FINDING L AND U MATRIX:

![Screenshot (127)](https://github.com/Subalakshmisuresh/LU-Decomposition/assets/121957896/8690954c-64ff-4153-8416-6409f0fcb878)

## OUTPUT FOR LU DECOMPOSITION:

![Screenshot (128)](https://github.com/Subalakshmisuresh/LU-Decomposition/assets/121957896/c5e03ac3-b208-47ff-ad4f-c48a993c56ba)




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

