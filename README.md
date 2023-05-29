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
# Register No: 212222100030
# Developed By: E.NANDHINI
# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)

# 2-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)

# Infinity Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)

```
## Output:
### 1-Norm of a Matrix

![1 norm](https://github.com/Nandhinijaya/Norm-of-a-matrix/assets/121998147/355005a6-49c7-458a-8735-1a36f6eda04a)


### 2-Norm of a Matrix


![2 norm](https://github.com/Nandhinijaya/Norm-of-a-matrix/assets/121998147/c4e66ce6-2c1d-4ca7-b089-73be949690d4)



### Infinity Norm of a Matrix


![infinity norm](https://github.com/Nandhinijaya/Norm-of-a-matrix/assets/121998147/f656cb70-5000-45cc-825d-47bc47c7c439)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
