# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
(i)

1. Start the program

2. Read the input matrix from the user and convert it into a NumPy array A

3. Import required libraries, NumPy for matrix operations and lu function from SciPy

4. Perform LU decomposition by applying lu(A) to obtain permutation matrix P, lower triangular matrix L, and upper triangular matrix U

5. Display the results by printing the L and U matrices, then terminate the program

(ii)

1. Start the program

2. Read the input matrices Read coefficient matrix A and constant matrix B, and convert them into NumPy arrays

3. Import required libraries Import NumPy and lu_factor, lu_solve functions from SciPy

4. Perform LU factorization Apply lu_factor(A) to decompose matrix A into LU form and obtain pivot indices

5. Solve the system and display result Use lu_solve((lu, piv), B) to find solution X, print the result, and stop the program 

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by:Leena shree M 
RegisterNumber:212225220056
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
Developed by: Leena shree M 
RegisterNumber:212225220056
import numpy as np
from scipy.linalg import lu_factor, lu_solve
A= np.array(eval(input()))
B= np.array(eval(input()))
lu , piv = lu_factor(A)
X=lu_solve((lu,piv),B)
print(X)
 
*/
```

## Output:
![lu decomposition]()

<img width="1296" height="599" alt="image" src="https://github.com/user-attachments/assets/2082f12a-0b9d-4431-a3cc-43ca1e85336b" />
<img width="1184" height="334" alt="image" src="https://github.com/user-attachments/assets/4ab668ab-f3cb-4beb-a061-bb5396483a3b" />



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

