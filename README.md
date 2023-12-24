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
```
#Python
# Register No:23012881
# Developed By:SETHUKKARASI C
# 1-Norm of a Matrix

import numpy as np
arr=np.array(eval(input()))
norm=np.linalg.norm(arr,1)
print("{:.2f}".format(norm))


# 2-Norm of a Matrix

import numpy as np
arr=np.array(eval(input()))
norm=np.linalg.norm(arr,2)
print("{:.2f}".format(norm))


# Infinity Norm of a Matrix


import numpy as np
arr=np.array(eval(input()))
norm=np.linalg.norm(arr,np.inf)
print("{:.2f}".format(norm))


```
## Output:
### 1-Norm of a Matrix
<br>![1](https://github.com/SETHUKKARASI3006/Norm-of-a-matrix/assets/144979338/62ff153a-b6a4-4afb-beff-3722156be3d9)
<br>
<br>

### 2-Norm of a Matrix
<br>![2](https://github.com/SETHUKKARASI3006/Norm-of-a-matrix/assets/144979338/0cdb1366-04e2-47d6-ba0e-272481dedb32)
<br>
<br>

### Infinity Norm of a Matrix
<br>![3](https://github.com/SETHUKKARASI3006/Norm-of-a-matrix/assets/144979338/3cf1ac71-a717-4a7f-a682-b4aabccc026f)
<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
