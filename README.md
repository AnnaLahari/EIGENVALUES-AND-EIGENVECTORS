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
Prepare the lists from each linear equations and assign in np.array().
### Step 3:
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4:
End the program.
## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: A.LAHARI
#RegisterNumber:23002931
import numpy as np
A=[[2,-3,0],[2,-5,0],[0,0,3]]
values,vectors=np.linalg.eig(A)
print("Eigen values are",values,"and Eigen Vectors are",vectors)

```
## Output:
![image](https://github.com/AnnaLahari/EIGENVALUES-AND-EIGENVECTORS/assets/149365425/a858e954-5fd3-494b-81f6-91806923b125)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
