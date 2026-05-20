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
# Register No: 212225220108
# Developed By:Sujan S
# 1-Norm of a Matrix
import numpy as np
InputArray=np.array(eval(input()))
OneNorm=np.linalg.norm(InputArray,1)
print(OneNorm)





# 2-Norm of a Matrix
import numpy as np
InputArray=np.array(eval(input()))
TwoNorm=np.linalg.norm(InputArray,2)
print(f"{TwoNorm:.2f}")




# Infinity Norm of a Matrix
import numpy as np
InputArray=np.array(eval(input()))
InfinityNorm=np.linalg.norm(InputArray,np.inf)
print(InfinityNorm)






```
## Output:
### 1-Norm of a Matrix
<img width="1277" height="827" alt="image" src="https://github.com/user-attachments/assets/ce4d109b-b56d-42f2-b2ad-9182aefc2149" />


### 2-Norm of a Matrix
<img width="1111" height="705" alt="image" src="https://github.com/user-attachments/assets/be608797-05f8-458f-b1f3-45df5d46b8c6" />


### Infinity Norm of a Matrix
<img width="1293" height="661" alt="image" src="https://github.com/user-attachments/assets/38b9ea86-2f61-4bd4-8e47-6a5579d3da1d" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
