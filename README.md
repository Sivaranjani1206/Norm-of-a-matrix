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
# 1-Norm of a Matrix
'''
Program to find 1-norm of a matrix.
Developed by: SIVARANJANI M
RegisterNumber: 212225220099
'''
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```

```
# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: SIVARANJANI M
RegisterNumber: 212225220099
'''
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```

```
# Infinity Norm of a Matrix
'''
Program to find Infinity-norm of a matrix.
Developed by: SIVARANJANI M
RegisterNumber: 212225220099
'''
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat, np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

```
## Output:
### 1-Norm of a Matrix

<img width="1290" height="881" alt="Screenshot 2026-11-01 163004" src="https://github.com/user-attachments/assets/645fc76f-fce9-48b5-84fc-7c12ffa4316c" />

### 2-Norm of a Matrix

<img width="1293" height="886" alt="Screenshot 2026-11-01 163103" src="https://github.com/user-attachments/assets/047c14e7-7ac7-4933-8cd0-b94e3b4a19a9" />

### Infinity Norm of a Matrix

<img width="1295" height="886" alt="Screenshot 2026-11-01 163120" src="https://github.com/user-attachments/assets/fa21efd6-5864-4135-90bd-39558b908214" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
