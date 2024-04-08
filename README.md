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
# Developed By:Stephen raj.Y
# 1-Norm of a Matrix
#developed by :STEPHEN RAJ.Y
#REGISTER NO:212223230217
import numpy as np
mat =eval(input())
a=np.linalg.norm(mat,1)
print("%0.2f"%a)




# 2-Norm of a Matrix
#developed by :STEPHEN RAJ.Y
#REGISTER NO:212223230217
import numpy as np
mat =eval(input())
a=np.linalg.norm(mat,2)
print("%0.2f"%a)




# Infinity Norm of a Matrix
#developed by :STEPHEN RAJ.Y
#REGISTER NO:212223230217
import numpy as np
mat =eval(input())
a=np.linalg.norm(mat,np.inf)
print("%0.2f"%a)





```
## Output:
### 1-Norm of a Matrix
![Screenshot 2024-04-08 072503](https://github.com/23002248/Norm-of-a-matrix/assets/151701774/a5e2ae85-e747-4dc0-b6df-5bac1191954a)


### 2-Norm of a Matrix
![Screenshot 2024-04-08 072546](https://github.com/23002248/Norm-of-a-matrix/assets/151701774/7578a630-d476-4e1c-8546-4a942eb500d5)


### Infinity Norm of a Matrix
![Screenshot 2024-04-08 072624](https://github.com/23002248/Norm-of-a-matrix/assets/151701774/4095af00-d434-4db8-b003-add39d714998)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
