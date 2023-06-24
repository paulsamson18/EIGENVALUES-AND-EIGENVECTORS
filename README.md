# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Imoprt numpy as np
### Step 2: 
Assign a variable and store the array of matrix
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program

## Program:
```
import numpy as np
A=np.array([[4,2] ,[2,4]])
evalues,evector=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(evalues,evector))
```

## Output:
![image](https://github.com/paulsamson18/EIGENVALUES-AND-EIGENVECTORS/assets/119405794/e6e06ca4-533b-4acc-a25e-b7fad4f43c22)


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
