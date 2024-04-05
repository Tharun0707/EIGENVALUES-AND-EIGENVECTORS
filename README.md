# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import numpy module.
### Step 2: 
Introduce varible m.
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
Print V.

## Program:
#Program to find the eigen values and eigen vectors.
#Developed by:Tharun Sridhar 
#RegisterNumber:212223230230
import numpy as np
m = np.array([[2,-3,0], 
              [2,-5,0], 
              [0,0,3]])
w, v = np.linalg.eig(m)
print("Eigen values are",w,"and Eigen Vectors are",v)

## Output:
![image](https://github.com/Tharun0707/EIGENVALUES-AND-EIGENVECTORS/assets/145548496/04a9e2cd-c41c-4b95-83b3-06d7fdd245b2)
![image](https://github.com/Tharun0707/EIGENVALUES-AND-EIGENVECTORS/assets/145548496/c7761c05-0c34-4216-8b33-26541732157b)



## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
