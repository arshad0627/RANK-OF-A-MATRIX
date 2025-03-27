# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1:
Import the numpy module to use the build-in function for calculation

### Step 2:
Prepare the lists from each linear equations and assign in np.array()

### Step 3:
Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.

### Step 4:
End the program
## Program:
```
#Program to find the rank of a matrix.
#Developed by: MOHAMED ARSHADULLAH A
#RegisterNumber: 212224230161
import numpy as np
matrix = [[5, -3, -10],
          [2, 2, -3],
          [-3, -1, 5]]
matrix_np = np.array(matrix)
rank = np.linalg.matrix_rank(matrix_np)
print( rank)
```
## Output:

![Screenshot 2025-03-27 174208](https://github.com/user-attachments/assets/f41c0719-cd81-47fc-a6c6-edff47f400de)

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

