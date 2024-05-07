# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
## Step 1:
Get the input matrix using np.array()   
## Step 2:
Find the 2-norm of the matrix using np.linalg.norm()
## Step 3:
Print the norm of the matrix in two decimal places.

## Program:

# 1-Norm of a Matrix
```Python
'''
Program to find 1-Norm of a matrix
Developed by : N.PRAVESH
Register no : 212223230154
'''
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)
```

# 2-Norm of a Matrix

```python
'''
Program to find 2-norm of a matrix.
Developed by: N.PRAVESH
RegisterNumber: 212223230154
'''
import numpy as np

mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)
```

# Infinity Norm of a Matrix

```python
'''
Program to find infinity-norm of a matrix.
Developed by : N.PRAVESH
RegisterNumber : 212223230154
'''

import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)
```
## Output:
### 1-Norm of a Matrix

![Screenshot 2024-05-07 084923](https://github.com/NPravesh2005/Norm-of-a-matrix/assets/164477756/e5e51e99-1e19-4258-94a5-484a6aed9d3e)

### 2-Norm of a Matrix

![Screenshot 2024-05-07 084948](https://github.com/NPravesh2005/Norm-of-a-matrix/assets/164477756/4c33e229-e2cb-457b-b383-d33bab18a062)


### Infinity Norm of a Matrix

![Screenshot 2024-05-07 085010](https://github.com/NPravesh2005/Norm-of-a-matrix/assets/164477756/0a0ca291-e1d8-4f60-92fc-3fa0a4d24872)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
