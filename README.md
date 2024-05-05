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
Program to find the 1-Norm of a matrix and display the results in two decimal places.
Developed by : ROGITH. K
Register number: 212223110042
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_mat="{:.2f}".format(ans)
print(norm_of_mat)



# 2-Norm of a Matrix

'''
Program to find 2-norm of a matrix.
Developed by: ROGITH. K
RegisterNumber: 212223110042 
'''
import numpy as np
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_mat="{:.2f}".format(ans)
print(norm_of_mat)



# Infinity Norm of a Matrix

'''
Program to find Infinity norm of a matrix.
Developed by: ROGITH. K
RegisterNumber: 212223110042
'''
import numpy as np
mat=np.array(eval(input()))

norm=np.linalg.norm(mat,ord=np.inf)
print("{:.2f}".format(norm))

```
## Output:
### 1-Norm of a Matrix
![alt text](<Screenshot 2024-04-27 094040.png>)

### 2-Norm of a Matrix
![alt text](<Screenshot 2024-04-27 094100.png>)

### Infinity Norm of a Matrix
![alt text](<Screenshot 2024-04-27 094114.png>)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
