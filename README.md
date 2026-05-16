# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:

### Step1 :  Write a python program for the given matrix.
### Step 2: Using numpy library.
### Step 3:  Using linalg.inv(),we can get the inverse of the matrix.
### Step 4:  Run the program and get the output.

## Program:
```
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a=np.array([[1,0,3],[-1,2,-2],[2,3,-1]])
b=np.linalg.inv(a)
print(b)
```
## Output:

<img width="915" height="786" alt="image" src="https://github.com/user-attachments/assets/2098ae79-c0a2-4a47-8805-ee0140f08afb" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

