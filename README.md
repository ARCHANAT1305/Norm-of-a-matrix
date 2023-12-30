# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1. Get the input matrix using np.array()
2. Find the 2-norm of the matrix using np.linalg.norm()
3. Print the norm of the matrix in two decimal places
## Program:
```
# Register No: 212223240013
# Developed By: ARCHANA.T

# 1-Norm of a Matrix

import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)

# 2-Norm of a Matrix

import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
Norms_of_matrix = "{:.2f}".format(ans)
print(Norms_of_matrix)

# Infinity Norm of a Matrix

import numpy as np

mat = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
norm_of_matrix = "{:.2f}".format(ans)
print(norm_of_matrix)

```
## Output:

### 1-Norm of a Matrix
![1 NORM](https://github.com/ARCHANAT1305/Norm-of-a-matrix/assets/145975189/507c1046-81be-4e92-8885-3950ac834725)


### 2-Norm of a Matrix
![2 NORM](https://github.com/ARCHANAT1305/Norm-of-a-matrix/assets/145975189/cf492781-5e9b-4179-b311-e488aaa97f8c)



### Infinity Norm of a Matrix
![INFINITY NORM](https://github.com/ARCHANAT1305/Norm-of-a-matrix/assets/145975189/9b72ca71-177d-49ff-b5b7-9e06eb01eba4)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
