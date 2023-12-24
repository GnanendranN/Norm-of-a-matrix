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
# Register No: 23006661
# Developed By: Gnanendran
# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

# 2-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

# Infinity Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```
## Output:
### 1-Norm of a Matrix
![ex7-1](https://github.com/GnanendranN/Norm-of-a-matrix/assets/138955207/64dace37-dd1d-4846-b590-0fe0793dc28f)

### 2-Norm of a Matrix
![ex7-2](https://github.com/GnanendranN/Norm-of-a-matrix/assets/138955207/95b8c1af-4884-4193-9b35-efebc7e47186)

### Infinity Norm of a Matrix
![ex7-3](https://github.com/GnanendranN/Norm-of-a-matrix/assets/138955207/f5866a7d-6bb6-4424-8d62-f0e12755e24d)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
