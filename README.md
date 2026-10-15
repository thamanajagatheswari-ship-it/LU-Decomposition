# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm: LU Decomposition
5.a
1.Start the program and import the required python libraries 
2. Read the input matrix and initialize the L and U
3.Calculate the L and U matrix using the LU Decomposition method 
4. Display the L and U matrices and stop the program
5.b
1.Start the program and import the required python libraries 
2. Read the input matrix and initialize the L and U
3.Calculate the L and U matrix using the LU Decomposition method 
4. Display the L and U matrices and stop the program

## Program:
(i) To find the L and U matrix
### Program to find L and U matrix using LU decomposition.
### Developed by: Thamana G
### RegisterNumber:26018758
### import os
### os.environ["OPENBLAS_NUM_THREADS"]="1"
### import numpy as np
### from scipy.linalg import lu
### A=np.array(eval(input()))
### P,L,U=lu(A)
### print(L)
### print(U)
/*
## program:
(ii) To find the LU Decomposition of a matrix
### Program to find the LU Decomposition of a matrix.
### Developed by: Thamana G
### RegisterNumber:26018758
### Program to solve a matrix using LU decomposition.
### Developed by: Thamana G
### RegisterNumber:26018758 
### import os
### os.environ["OPENBLAS_NUM_THREADS"]="1"
### import numpy as np
### from scipy.linalg import lu_factor,lu_solve
### a=np.array(eval(input()))
### b=np.array(eval(input()))
### l,p=lu_factor(a)
### x=lu_solve((l,p),b)
### print(x)
/*

## Output:
![lu decomposition]
5.a
(<img width="982" height="813" alt="Screenshot 2026-10-15 175516" src="https://github.com/user-attachments/assets/bb92d781-d802-4c9e-8805-0f22246a8b76" />)

5.b
<img width="1137" height="621" alt="Screenshot 2026-10-15 181922" src="https://github.com/user-attachments/assets/587d46d1-8609-467c-9622-94d0320819a0" />


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

