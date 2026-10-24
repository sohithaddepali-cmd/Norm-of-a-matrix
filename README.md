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
# Register No:26013079
# Developed By:A.Sohith
# 1-Norm of a Matriximport os
os.environ["OPENBLAS_NUM_THREADS"]="1"
 
import numpy as np
A=np.array(eval(input()))
norm1=np.linalg.norm(A,1)
norm="{:.2f}".format(norm1)
print(norm)




# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: A.Sohith
RegisterNumber: 26013079
'''
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy as np
A=np.array(eval(input()))
norm1=np.linalg.norm(A,2)
norm="{:.2f}".format(norm1)
print(norm)



# Infinity Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy as np
A=np.array(eval(input()))
norm1=np.linalg.norm(A,np.inf)
norm="{:.2f}".format(norm1)
print(norm)




```
## Output:
### 1-Norm of a Matrix
<br><img width="912" height="305" alt="image" src="https://github.com/user-attachments/assets/3e0d14a8-1256-4d24-8f61-c52e1d0298fe" />

<br>
<br>

### 2-Norm of a Matrix
<br><img width="940" height="357" alt="image" src="https://github.com/user-attachments/assets/7a2482b9-da2c-4087-81dd-62fb5060bc23" />

<br>
<br>

### Infinity Norm of a Matrix
<br><img width="837" height="320" alt="image" src="https://github.com/user-attachments/assets/7b2c4561-9339-464d-924f-e18a2dad4207" />

<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
