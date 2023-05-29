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


![1 norm](https://github.com/Nandhinijaya/Norm-of-a-matrix/assets/121998147/3b693302-a0d5-4e60-9aa1-a52594d92d7d)


### 2-Norm of a Matrix


![2 norm](https://github.com/Nandhinijaya/Norm-of-a-matrix/assets/121998147/cedd6df5-c631-4036-b5c4-12b128c5907c)

### Infinity Norm of a Matrix


![infinity norm](https://github.com/Nandhinijaya/Norm-of-a-matrix/assets/121998147/10a13267-e0ab-4112-81f1-d0efa4e2e83b)



## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
