# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in function for calculation
### Step 2: Prepare the list from matrix and assign in np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: End the program

## Program:
#Program to find the eigen values and eigen vectors.
#Developed by: A.Aira Dario
#RegisterNumber:25016155
```
import numpy as np
A=np.array([[2,2],[1,3]])
values,vectors=np.linalg.eig(A)
print(f"Eigen values are {values} and Eigen Vectors are {vectors}")
```
## Output:
<img width="1920" height="1200" alt="Screenshot 2025-11-22 145339" src="https://github.com/user-attachments/assets/78c06ce5-c3a3-4d77-8e75-f004aaab0a4e" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
