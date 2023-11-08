# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import numpy as np
### Step 2: 
Get input as a=np.array(eval(input()))
### Step 3:
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
Program to find the eigen values and eigen vectors.
## Program:

import numpy as np

a = np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])

values,vectors = np.linalg.eig(a)

print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))


## Output:

![Screenshot (13)](https://github.com/maha712/EIGENVALUES-AND-EIGENVECTORS/assets/121156360/5bb3d45e-eeb9-4c03-a241-157d64f507a8)


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
