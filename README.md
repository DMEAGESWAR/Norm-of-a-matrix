# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
Step 1: Input Matrix
Read a matrix from the user and store it in a NumPy array mat.

Step 2: Calculate 1-Norm
Use the np.linalg.norm function with the ord=1 parameter to calculate the 1-norm of the matrix mat. Store the result in the variable ans.

Step 3: Format Result
Format the result ans to two decimal places using the "{:.2f}".format function. Store the formatted result in the variable norm_of_matrix.

Step 4: Print Result
Print the formatted result norm_of_matrix.

## Program:
```Python
# Register No: 24900815
# Developed By: D MEAGESWAR
# 1-Norm of a Matrix

import numpy as np

mat=np.array(eval(input()))

ans=np.linalg.norm(mat,1)

norm_of_matrix="{:.2f}".format(ans)

print(norm_of_matrix)




# 2-Norm of a Matrix:

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)




# Infinity Norm of a Matrix:
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)





```
## Output:
### 1-Norm of a Matrix
![Screenshot 2024-11-27 191629](https://github.com/user-attachments/assets/9389233a-8027-40f0-a8ed-44f098ce4b18)


### 2-Norm of a Matrix
![Screenshot 2024-11-27 192000](https://github.com/user-attachments/assets/35e80748-8d87-4c5f-bfdb-6bad9e66a8dc)

### Infinity Norm of a Matrix
![Screenshot 2024-11-27 192007](https://github.com/user-attachments/assets/50d728b2-667a-4464-88f6-276f1114ff32)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
