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
# 1-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: KISHOR KUMAR B.
RegisterNumber: 212223240072
'''
import numpy as np
value = eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,1)
print('{:.2f}'.format(norm))




# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: KISHOR KUMAR B.
RegisterNumber: 212223240072
'''
import numpy as np
value = eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,2)
print('{:.2f}'.format(norm))




# Infinity Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: KISHOR KUMAR B.
RegisterNumber: 212223240072
'''
import numpy as np
value = eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,np.inf)
print('{:.2f}'.format(norm))





```
## Output:
### 1-Norm of a Matrix
![1](https://github.com/Kishorerz/Norm-of-a-matrix/assets/144451216/9ba64325-43ee-49d1-a026-bddc8994cbc7)

### 2-Norm of a Matrix
![2](https://github.com/Kishorerz/Norm-of-a-matrix/assets/144451216/45bfdbd4-5f0b-4746-973b-1675f485227b)

### Infinity Norm of a Matrix
![3](https://github.com/Kishorerz/Norm-of-a-matrix/assets/144451216/251fd52f-eaed-4ebc-9dcb-32d47fbb9fa5)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
