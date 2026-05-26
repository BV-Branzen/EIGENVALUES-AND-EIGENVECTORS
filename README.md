# EIGENVALUES-AND-EIGENVECTORS

~~~
Nmae: Branzen B V
Register No: 212225100005
~~~

## Aim:

To write a python program to find the Eigenvalues and Eigen Vectors

## Equipment’s required:

1. 	Hardware – PCs

2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm:

### Step1 :
Import the numpy module to use the built-in functions for calculation

### Step 2:
Prepare the lists from each linear equations and assign in np.array()

### Step 3:
Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

### Step 4:
End the program

## Program:

Write a program to find the eigenvalues and associated eigenvectors for the matrix
[2,-3,0],[2,-5,0],[0,0,3]

~~~
#Program to find the eigen values and eigen vectors.
#Developed by: 
#RegisterNumber:
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a= np.array([[2,-3,0],[2,-5,0],[0,0,3]])
values,vectors=np.linalg.eig(a)
print('Eigen values are {} and Eigen Vectors are {} '.format(values,vectors))
 

~~~

## Output:

<img width="1229" height="211" alt="4" src="https://github.com/user-attachments/assets/47dd1168-3858-4c2c-9762-28504432e931" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
