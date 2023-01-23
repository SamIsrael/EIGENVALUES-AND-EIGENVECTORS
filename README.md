# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
### Step 2: 
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 

## Program:

```
#Program to find the eigen values and eigen vectors.
#Developed by: Sam Israel D
#RegisterNumber: 22008392

import numpy as np
a = np.array([[2,2],[1,3]])
values,vector = np.linalg.eig(a)
print("Eigen values are",values,"and Eigen Vectors are",vector)
```

## Output:

![image](./eigen.png)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
