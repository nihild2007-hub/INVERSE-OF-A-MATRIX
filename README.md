# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
```
Import the numpy module to use the built-in functions for calculation

Step 2:
Prepare the lists from each linear equations and assign in np.array()

Step 3:
Using np.linalg.inv(),we can find the inverse of a matrix

Step 4:
End the program
```

## Program:
```
#Developed by: Mohamed Ukkas R
#RegisterNumber: 212225040245

import os 
os.environ["OPENBLAS_NUM_THREADS"] = "1"
import numpy as np
matrix_A = np.array([[6, 2, 3], [3, 1, 1], [10, 3, 4]])
result = np.linalg.inv(matrix_A)
print(result)
```
## Output:
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/5afdf09f-41b6-4a26-bd0a-8823045d00d4" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

