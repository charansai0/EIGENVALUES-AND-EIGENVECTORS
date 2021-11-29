# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: START THE PROGRAM
### Step 2: IMPROT THE NYUMPY AS NP 
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: END THE PROGRAM 

## Program:
#Program to find the eigen values and eigen vectors.

#Developed by: v.charan sai 

#RegisterNumber: 21003158

import numpy as np

A = np.array([[4,2],[2,4]])

values,vectors=np.linalg.eig(A)

print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))

## Output:
![OUTPUT](https://github.com/charansai0/EIGENVALUES-AND-EIGENVECTORS/blob/main/Screenshot%20(112).png?raw=true)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
