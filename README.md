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
# Register No:212225230148
# Developed By:lavanya g
# 1-Norm of a Matrix

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrix=eval(input())
one_matrix=np.linalg.norm(matrix,1)
print("{:.2f}".format(one_matrix))


# 2-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1" 
import numpy as np
matrix=eval(input())
two_matrix=np.linalg.norm(matrix,2)
print("{:.2f}".format(two_matrix)) 


# Infinity Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np 
matrix=eval(input())
inf_matrix=np.linalg.norm(matrix,np.inf)
print("{:.2f}".format(inf_matrix)) 




```
## Output:
### 1-Norm of a Matrix
<br>
<<img width="772" height="782" alt="image" src="https://github.com/user-attachments/assets/e76726e4-8fcc-469c-96cf-715e0ba311a8" />

<br>

### 2-Norm of a Matrix
<br>
<img width="686" height="763" alt="image" src="https://github.com/user-attachments/assets/8b3053ed-0bda-4838-a420-5c383b1c4e0c" />

<br>

### Infinity Norm of a Matrix
<br>
<<img width="831" height="798" alt="image" src="https://github.com/user-attachments/assets/d5d62368-3eeb-471d-aa6f-6973fad3deb7" />

<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
