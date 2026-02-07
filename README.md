# RANK-OF-A-MATRIX
## Name: Roshini A
## Register Number: 212224230233
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Read the matrix
### Step 2: 
Convert the matrix into row echelon form using row operations.
### Step 3:
Using the np.linalg.solve(), we can find the solutions.
### Step 4: 
End the program
## Program:
```
import numpy as np
A = np.array([[3,2,5],[1,1,2],[3,3,6]])
rank = np.linalg.matrix_rank(A) 
print(rank)

```
## Output:
<img width="1303" height="269" alt="image" src="https://github.com/user-attachments/assets/68d829ea-33e3-4020-bd7f-846d17b45fce" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.
