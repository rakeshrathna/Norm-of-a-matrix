NORM OF MATRIX
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
# Register No: 212224040265
# Developed By: RAKESH RATHNA M
# 1-Norm of a Matrix
import numpy as np
m=np.array(eval(input()))
a=np.abs(m)
s=np.sum(a,axis=0)
ma=np.max(s)
print(ma)




# 2-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
l2=np.linalg.norm(mat,2)
print(f"{l2:.2f}")





# Infinity Norm of a Matrix


import numpy as np
mat=np.array(eval(input()))
infinity=np.linalg.norm(mat,np.inf)
print(f"{infinity:.2f}")




```
## Output:
### 1-Norm of a Matrix
![445507138-5e7bf3b8-868d-4726-87e4-141c24c2eae6](https://github.com/user-attachments/assets/0f1d7534-2e53-4bad-a356-742af7cf8ebf)

### 2-Norm of a Matrix
![445507276-9b7bfb83-d0cb-4c02-81f6-8ad1e1eaf64f](https://github.com/user-attachments/assets/9c7dc7f6-07e1-4182-95ca-00078f3c49d6)


### Infinity Norm of a Matrix
![445507471-56b1b6ac-fc46-4af6-bb43-bd741f43a36b](https://github.com/user-attachments/assets/59530cec-a15a-4c24-9bea-379ffa0a0252)




## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
