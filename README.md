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
# Register No: 25015346
# Developed By: MANOJ KUMAR N
# 1-Norm of a Matrix
import numpy as np
matrix=eval(input())
one_matrix=np.linalg.norm(matrix,1)
print(f"{one_matrix:.2f}")



# 2-Norm of a Matrix
import numpy as np
matrix=eval(input())
two_matrix=np.linalg.norm(matrix,2)
print("{:.2f}".format(two_matrix))




# Infinity Norm of a Matrix
import numpy as np
matrix=eval(input())
inf_matrix=np.linalg.norm(matrix,np.inf)
print("{:.2f}".format(inf_matrix))




```
## Output:
### 1-Norm of a Matrix
<img width="1462" height="715" alt="Mathsforai ex-7(a)" src="https://github.com/user-attachments/assets/0d6c4dbf-26c8-4e8f-8337-4b0c0d7b7280" />


### 2-Norm of a Matrix
<img width="1473" height="775" alt="Mathsforai ex-7(b)" src="https://github.com/user-attachments/assets/93f2ff89-4e42-455a-90f3-d22bee6f4d4e" />


### Infinity Norm of a Matrix
<img width="1463" height="703" alt="Mathsforai ex-7(c)" src="https://github.com/user-attachments/assets/1d541e02-0832-474b-9bd0-027032a16427" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
