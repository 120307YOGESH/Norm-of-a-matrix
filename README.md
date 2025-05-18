# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
```
1. Get the input matrix using np.array()   
2. Find the 2-norm of the matrix using np.linalg.norm()
3. Print the norm of the matrix in two decimal places.
## Program:
```

#PROGRAM:
```Python
# Register No: 212224230311
# Developed By: S.YOGESH
# 1-Norm of a Matrix

import numpy as np
mat =np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix = "{:.2f}".format(ans)
print(norm_of_matrix)


# 2-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix='{:.2f}'.format(ans)
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

![image](https://github.com/user-attachments/assets/4b10c1d5-5428-4f33-9094-ef3a7df5b120)


### 2-Norm of a Matrix

![image](https://github.com/user-attachments/assets/bebdefb4-a7aa-48cc-844a-a58e627aa67c)


### Infinity Norm of a Matrix

![image](https://github.com/user-attachments/assets/74d0ef74-96c9-454c-9626-8ee8c02489df)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
