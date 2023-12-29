# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1. Get the input matrix using np.array()   
2. Find the 2-norm of the matrix using np.linalg.norm()
3. Print the norm of the matrix in two decimal places.
## Program:
```Python
program to find 1-norm of a matrix.
Developed by: Abdul kalaam k m
RegisterNumber: 23005114

import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
nom="{:.2f}".format(ans)
print(nom)
```




# 2-Norm of a Matrix
```
Program to find 2-norm of a matrix.
Developed by: abdul kalaam k m
RegisterNumber: 23005114

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
nom="{:.2f}".format(ans)
print(nom)
```




# Infinity Norm of a Matrix
```
Program to find Infinity Norm of a Matrix.
Developed by: abdul kalaam k m
RegisterNumber: 23005114

import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
nom="{:.2f}".format(ans)
print(nom)




```
## Output:

### 1-Norm of a Matrix
![Screenshot 2023-12-29 180416](https://github.com/dfghytr/Norm-of-a-matrix/assets/138970628/47d38b65-a68e-4b43-9e3e-5bb4a2e80d5d)


### 2-Norm of a Matrix
![Screenshot 2023-12-29 180428](https://github.com/dfghytr/Norm-of-a-matrix/assets/138970628/d6f2c048-113c-413f-98cf-8c5c024942da)


### Infinity Norm of a Matrix
![Screenshot 2023-12-29 180439](https://github.com/dfghytr/Norm-of-a-matrix/assets/138970628/24dc8ed2-b73d-4b32-8cc2-c6dbe263c397)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
