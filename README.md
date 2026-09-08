# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the NumPy library using import numpy as np.
### Step 2: Define the matrix using a NumPy array.
### Step 3: Use the np.linalg.inv() function to find the inverse of the matrix.
### Step 4: Display the inverse matrix using the print() function.

## Program:
```python
#Program to find the inverse of a matrix.
#Developed by: Sadhana K
#RegisterNumber: 212225240128

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a=np.array([[1,0,3],[-1,2,-2],[2,3,-1]])
b=np.linalg.inv(a)
print(b)
```
## Output:

<img width="1007" height="226" alt="image" src="https://github.com/user-attachments/assets/62706427-3910-42f3-be86-dfaadc0d55a9" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

