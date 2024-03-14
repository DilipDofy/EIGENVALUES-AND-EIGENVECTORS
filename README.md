# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :
Import the numpy module to use the built-in functions for calculation.
### Step 2:
Prepare the lists from each equations and assign in np.array()
### Step 3:
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program
## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: DILIP MP
#RegisterNumber: 212223230048

import numpy as np
matrix=np.array([[-2,2,-3], [2,1,-6], [-1,-2,0]])
eigvalues, eigvectors=np.linalg.eig(matrix)
print("Eigen values are", eigvalues, "and Eigen Vectors are", eigvectors)
```
## Output:
![DilipDofy--4](https://github.com/DilipDofy/EIGENVALUES-AND-EIGENVECTORS/assets/147223497/78615bef-e21b-4496-84f1-bfffaf6ad203)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
