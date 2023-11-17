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
# Register No:
# Developed By:
# 1-Norm of a Matrix
import numpy as np
a=np.array(eval(input()))
sol=np.linalg.norm(a,1)
norm="{:.2f}".format(sol)
print(norm)

# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: yourname BOOBESH PM
RegisterNumber: 212222233001
'''
import numpy as np
a=np.array(eval(input()))
sol=np.linalg.norm(a,2)
norm="{:.2f}".format(sol)
print(norm)

# Infinity Norm of a Matrix
import numpy as np
a=np.array(eval(input()))
sol=np.linalg.norm(a,np.inf)
norm="{:.2f}".format(sol)
print(norm)
```
## Output:
### 1-Norm of a Matrix
![mat 7 1](https://github.com/Boobeshkrishna/Norm-of-a-matrix/assets/141472052/58135854-dad5-4958-8ae4-e392634a3e28)

### 2-Norm of a Matrix
![mat 7 2](https://github.com/Boobeshkrishna/Norm-of-a-matrix/assets/141472052/a61946cb-c6be-465e-96ee-42943c519ef5)

### Infinity Norm of a Matrix
![mat 7 3](https://github.com/Boobeshkrishna/Norm-of-a-matrix/assets/141472052/bcc5859e-fcc1-4beb-a3ab-c2d18f10453a)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
