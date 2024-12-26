# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
Program 1
 1. Get the input matrix using np.array()
 2. Find the 1-norm of the matrix using np.linalg.norm()
 3. Print the norm of the matrix in two decimal places.

Program 2
1. Get the input matrix using np.array()
2. Find the 2-norm of the matrix using np.linalg.norm()
3. Print the norm of the matrix in two decimal places.

Program 3
1. Get the input matrix using np.array()
2. Find the infinity-norm of the matrix using np.linalg.norm()
3. Print the norm of the matrix in two decimal places.

## Program:
```Python
# Register No: 24001394
# Developed By: Sadhana S
# 1-Norm of a Matrix
import numpy as np
arr=np.array(eval(input()))
result=np.linalg.norm(arr,1)
print(round(result))




# 2-Norm of a Matrix
import numpy as np
arr=np.array(eval(input()))
result=np.linalg.norm(arr,2)
print(round(result,2))





# Infinity Norm of a Matrix
import numpy as np
arr=np.array(eval(input()))
result=np.linalg.norm(arr,np.inf)
print(round(result))




```
## Output:
### 1-Norm of a Matrix
![Screenshot from 2024-12-26 12-10-25](https://github.com/user-attachments/assets/e53983e1-c8bc-41ce-a723-e97e515db740)


### 2-Norm of a Matrix
![Screenshot from 2024-12-26 12-10-34](https://github.com/user-attachments/assets/99499e75-5eac-4a76-b999-eaa31eb24e22)


### Infinity Norm of a Matrix
![Screenshot from 2024-12-26 12-10-42](https://github.com/user-attachments/assets/454853f8-fd70-412c-9666-fbcb0802274d)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
