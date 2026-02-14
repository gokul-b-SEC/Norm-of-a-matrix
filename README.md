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
# Register No:212225230076
# Developed By:GOKUL B
# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)





# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: GOKUL B
RegisterNumber: 212225230076
'''
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
<br>
<br>
<br>
<img width="853" height="282" alt="image" src="https://github.com/user-attachments/assets/5055445c-271b-431c-ac39-951779a419ea" />


### 2-Norm of a Matrix
<br>
<br>
<br>
<img width="853" height="312" alt="image" src="https://github.com/user-attachments/assets/5237453e-863a-48ba-8cee-1f7f53e90583" />


### Infinity Norm of a Matrix
<br>
<br>
<br>
<img width="852" height="283" alt="image" src="https://github.com/user-attachments/assets/5168ef36-767f-4650-ac83-5f1b7e4be3eb" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
