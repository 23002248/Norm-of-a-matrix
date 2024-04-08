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
# Register No:212223230217
# Developed By:stephen raj.Y
# 1-Norm of a Matrix
import numpy as np
mat=eval(input())
a=np.linalg.norm(mat,1)
print("%0.2f"%a)

# 2-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_mat="{:.2f}".format(ans)
print(norm_mat)


# Infinity Norm of a Matrix

import numpy as np
mat=eval(input())
a=np.linalg.norm(mat,np.inf)
print("%0.2f"%a)

```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/etjabajasphin/Norm-of-a-matrix/assets/151701774/1ff86b34-e1ff-4572-ad87-4bc28c5509f5)



### 2-Norm of a Matrix
![image](https://github.com/etjabajasphin/Norm-of-a-matrix/assets/151701774/8afd07b3-829e-4f5d-8ef9-b0b249e49afc)

### Infinity Norm of a Matrix
![image](https://github.com/etjabajasphin/Norm-of-a-matrix/assets/151701774/21a38f74-34c9-4fb4-bea9-f5a46c20339f)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
