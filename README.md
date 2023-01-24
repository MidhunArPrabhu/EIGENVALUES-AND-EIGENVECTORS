# EIGENVALUES-AND-EIGENVECTORS
## AIM :

To write a python program to find the Eigenvalues and Eigen Vectors

## EQUIPMENTS REQUIRED :
- Hardware - PC
- naconda – Python 3.7 Installation / Moodle-Code Runner
## ALGORITHIM :

### STEP 1 : Import numpy library as np.

### STEP 2 : Create a matrix using array() function.

### STEP 3 : Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

### STEP 4 : Get the output and end the program.


## PROGRAM :
```python
#Program to find the eigen values and eigen vectors.
#Developed by: MIDHUN AZHAHU RAJA P
#RegisterNumber: 22008311

import numpy as np

a = np.array([[-2, 2, -3], [2, 1, -6], [-1, -2, 0]])
values, vectors = np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(values, vectors))
```
## OUTPUT :
![image](https://user-images.githubusercontent.com/118054670/214371451-1c7db822-eb6d-4039-bed1-2360e714f17a.png)

## RESULT :
Thus the Eigenvalue and Eigenvector is successfully solved using python program
