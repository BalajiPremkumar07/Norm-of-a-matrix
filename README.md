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
# Register No:26007368
# Developed By:Balaji
```
# 1-Norm of a Matrix
```
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
```

# 2-Norm of a Matrix

```
Program to find 2-norm of a matrix.
Developed by: Balaji.p
RegisterNumber: 26007368
'''
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
```


# Infinity Norm of a Matrix
```
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
print("{:.2f}".format(ans))

```


```
## Output:
### 1-Norm of a Matrix
<img width="1237" height="835" alt="image" src="https://github.com/user-attachments/assets/24937f3e-0f14-40bb-ab73-503b00af91fd" />



### 2-Norm of a Matrix

<img width="1243" height="880" alt="image" src="https://github.com/user-attachments/assets/ea22b768-59c7-4926-b65d-e9fccb85e02b" />


### Infinity Norm of a Matrix

<img width="1293" height="841" alt="image" src="https://github.com/user-attachments/assets/4163cd3e-0d75-41f1-829d-3719db149ecb" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
