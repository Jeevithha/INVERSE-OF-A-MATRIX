# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:

### Step1 : 
 import the numpy module to use the built in functions for calculation.
 
### Step 2: 
prepare the lists from each linear equations and assign in np.array().
### Step 3: 
using the np.linalg.solve(),we can fild the soltions.

### Step 4: 
End the program.

## Program:
```
#Program to find the inverse of a matrix.
#Developed by:jeevitha S 
#RegisterNumber:212222100016
import numpy as np 
A=np.array([[1,0,3],[-1,2,-2],[2,3,-1]])
inverse=np.linalg.inv(A)
print(inverse)
```
## Output:
![Screenshot (95)](https://user-images.githubusercontent.com/123623197/227886060-079a82ec-9ce7-421d-9aff-a7149441b7df.png)

## Result:
Thus the inverse of given matrix is successfully solved using python program

