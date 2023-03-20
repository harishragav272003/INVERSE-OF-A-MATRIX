# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy library: import numpy as np
### Step 2: 
Create a 3x3 numpy array A with the given values: A = np.array([[6,2,3],[3,1,1],[10,3,4]])
### Step 3: 
Compute the inverse of A using the np.linalg.inv() function and assign it to the variable inverse: inverse = np.linalg.inv(A)
### Step 4: 
Print the value of inverse using the print() function: print(inverse)

## Program:
```
#Program to find the inverse of a matrix.
#Developed by: HARISH RAGAV S
#RegisterNumber: 212222110013

import numpy as np
A= np.array([[6,2,3] ,[3,1,1] , [10,3,4]])
inverse = np.linalg.inv(A)
print(inverse)
```
## Output:
![image](https://user-images.githubusercontent.com/119345345/226252441-e14ec01e-848d-4810-aac8-cadcc34c7c3e.png)

## Result:
Thus the inverse of given matrix is successfully solved using python program

