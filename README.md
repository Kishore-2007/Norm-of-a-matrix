# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
Step 1. Get the input matrix using np.array()   
Step 2. Find the 2-norm of the matrix using np.linalg.norm()
Step 3. Print the norm of the matrix in two decimal places.
## Program:
```Python

# Register No:24900594
# Developed By:KISHORE.S


# 1-Norm of a Matrix
import numpy as np 
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)


# 2-Norm of a Matrix
import numpy as np 
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
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
![Screenshot 2024-12-04 135301](https://github.com/user-attachments/assets/740c8864-f6ab-48ff-a304-35a063ef9b6e)


### 2-Norm of a Matrix
![Screenshot 2024-12-04 135319](https://github.com/user-attachments/assets/0d1a20aa-0c49-43da-9a80-49670c7ab14f)


### Infinity Norm of a Matrix
![Screenshot 2024-12-04 135334](https://github.com/user-attachments/assets/c3e4d961-6517-4440-9ff9-48be84199f39)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
