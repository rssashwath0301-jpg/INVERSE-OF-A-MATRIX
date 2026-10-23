# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :  Import the numpy module to use the built-in functions for calculation
### Step 2: Prepare the lists from each equations and assign in np.array()
### Step 3: Using the np.linalg.inv(), we can find the inverse of the given matrix
### Step 4: End the program

## Program:
```
#Program to find the inverse of a matrix.
#Developed by: R S Sashwath
#RegisterNumber:26003043
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a=np.array([[6,2,3],[3,1,1],[10,3,4]])
r=np.linalg.inv(a)
print(r)
```
## Output:
<img width="530" height="217" alt="image" src="https://github.com/user-attachments/assets/e2dd86ba-4e43-443c-b5ca-0f8a5c193be7" />


## Result:
Thus the inverse of given matrix is successfully solved using python program

