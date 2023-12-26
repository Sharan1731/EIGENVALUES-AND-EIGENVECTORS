# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : import the numpy module to use the build in function fore calculation
### Step 2: prepare the lists from each linear eqaution and assign in np.array(
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: end tha progarm

## Program:
#Program to find the eigen values and eigen vectors.
#Developed by: Sharan G
#RegisterNumber:23002031
import numpy as np
A = np.array([[-2, 2, -3], [2, 1, -6], [-1, -2, 0]])
eigenvalues, eigenvectors = np.linalg.eig(A)
print("Eigen values are", eigenvalues, "and Eigen Vectors are", eigenvectors)

## Output:
![image](https://github.com/Sharan1731/EIGENVALUES-AND-EIGENVECTORS/assets/144980172/de0b863d-5564-471b-8d22-0a544c13d247)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
