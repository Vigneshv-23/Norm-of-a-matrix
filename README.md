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
# Register No:23002301
# Developed By:vignesh v
# 1-Norm of a Matrix
import numpy as np
matrix=np.array(eval(input()))
result=np.linalg.norm(matrix,1)
norm_of_matrix="{:.2f}".format(result)
print(norm_of_matrix)

# 2-Norm of a Matrix
import numpy as np
matrix=np.array(eval(input()))
result=np.linalg.norm(matrix,2)
norm_of_matrix="{:.2f}".format(result)
print(norm_of_matrix)
# Infinity Norm of a Matrix
import numpy as np
matrix=np.array(eval(input()))
result=np.linalg.norm(matrix,np.inf)
norm_of_matrix="{:.2f}".format(result)
print(norm_of_matrix)
```
## Output:
### 1-Norm of a Matrix
<img width="544" alt="image" src="https://github.com/Vigneshv-23/Norm-of-a-matrix/assets/110780412/e35f0263-abbf-4d34-9957-8eccb2371c44">


### 2-Norm of a Matrix
<img width="587" alt="image" src="https://github.com/Vigneshv-23/Norm-of-a-matrix/assets/110780412/8f15e2e7-99ab-4ad6-b19e-22140ff7adb9">

### Infinity Norm of a Matrix
<img width="596" alt="image" src="https://github.com/Vigneshv-23/Norm-of-a-matrix/assets/110780412/e2597da5-c0f2-4a41-b97a-c658667a6150">


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
