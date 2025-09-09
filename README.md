# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from the matrix and assign in np.array()
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program.
## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: SHARAN S
#RegisterNumber: 21222404039
import numpy as np
matrix = np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
eigen_values,eigen_vectors=np.linalg.eig(matrix)
print(f'Eigen values are {eigen_values} and Eigen Vectors are {eigen_vectors}')

```
## Output:
<img width="1247" height="730" alt="Screenshot 2025-09-09 133239" src="https://github.com/user-attachments/assets/c55ab8a5-7ad2-45b9-abb5-3da6096d2e98" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
