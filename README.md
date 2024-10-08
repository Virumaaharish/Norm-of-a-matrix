# DATE :
# EXP NO : 7
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

# Register No: 212223230246
# Developed By: M VIRUMAA HARISH

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

![Screenshot 2024-10-08 084019](https://github.com/user-attachments/assets/6a48426a-757e-447a-84e1-6f12ff2629f3)


### 2-Norm of a Matrix

![Screenshot 2024-10-08 084047](https://github.com/user-attachments/assets/d4c969c9-ec92-4a51-a305-f939a3386dc4)


### Infinity Norm of a Matrix

![Screenshot 2024-10-08 084059](https://github.com/user-attachments/assets/54bc5d8f-cf27-4c3b-8fc4-7db435fd6f37)


## Result

Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
