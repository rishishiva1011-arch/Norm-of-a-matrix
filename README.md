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
# Register No: 212225240118
# Developed By: Rishikesh S


# 1-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_mat="{:.2f}".format(ans)
print(Norm_mat)


# 2-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_mat="{:.2f}".format(ans)
print(Norm_mat)


# Infinity Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
print(ans)


```
## Output:
### 1-Norm of a Matrix

<img width="589" height="206" alt="EXP-7-i" src="https://github.com/user-attachments/assets/a71703ea-e2ab-4792-9e1b-a1ddaa723d69" />


### 2-Norm of a Matrix

<img width="591" height="231" alt="EXP-7-ii" src="https://github.com/user-attachments/assets/e8c3ba6e-49b1-4cba-91f1-b4c692349430" />


### Infinity Norm of a Matrix

<img width="586" height="208" alt="EXP-7-iii" src="https://github.com/user-attachments/assets/fc4d05c4-7cef-47a6-aa0c-cf33bf7a5d32" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
