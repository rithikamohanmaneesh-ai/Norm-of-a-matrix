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
Python
```
# Register No:212225100038
# Developed By:rithika
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

<img width="675" height="577" alt="image" src="https://github.com/user-attachments/assets/7b8b7866-5833-40bc-9f67-72932c228fdb" />


### 2-Norm of a Matrix

<img width="622" height="567" alt="image" src="https://github.com/user-attachments/assets/897067b3-8041-49ff-a4b3-2498f359a6f1" />


### Infinity Norm of a Matrix

<img width="526" height="592" alt="image" src="https://github.com/user-attachments/assets/35ee4705-a530-442d-af06-631a4b1205e9" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
