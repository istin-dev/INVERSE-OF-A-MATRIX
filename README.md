# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :  Import the required library (NumPy) to perform matrix operations.
### Step 2: Define the matrix for which the inverse has to be found.
### Step 3: Use the built-in function (np.linalg.inv()) to calculate the inverse of the matrix.
### Step 4: Display the inverse matrix as output. 

## Program:

```
import os
os.environ["OPENBLAS_NUM_THREADS"] = "1"

import numpy as np

A = np.array([[2,1,1],
     [1,1,1],
     [1,-1,2]])

A_inv = np.linalg.inv(A)

print(A_inv)

```

## Output:

<img width="1158" height="813" alt="image" src="https://github.com/user-attachments/assets/5c614d8e-b43d-47fb-9403-57644b510060" />


## Result:
Thus the inverse of given matrix is successfully solved using python program

