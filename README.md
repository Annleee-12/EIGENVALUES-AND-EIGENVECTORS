# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
Step1 :
Import library Numpy as np.

Step 2:
Define the matrix with the given values.

Step 3:
Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

Step 4:
Print the results using formatted string.

## Program:

```
import os

os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy as np

A = np.array([[2, 2], [1, 3]])

eigenvalues, eigenvectors = np.linalg.eig(A)

print("Eigen values are", eigenvalues, "and Eigen Vectors are", eigenvectors)
```
## Output:
<img width="1305" height="800" alt="image" src="https://github.com/user-attachments/assets/41582b3e-f1b8-4cd4-a2e3-6758447c0aa4" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
