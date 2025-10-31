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

# Register No: LOGU R
# Developed By:212224230141
# 1-Norm of a Matrix
```Python
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm = "{:.2f}".format(ans)
print(Norm)
```



# 2-Norm of a Matrix
```Python
import numpy as np
mat =np.array(eval(input()))
ans = np.linalg.norm(mat,2)
Norm = "{:.2f}".format(ans)
print(Norm)
```



# Infinity Norm of a Matrix

```Python
import numpy as np
mat  = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
Norm = "{:.2f}".format(ans)
print(Norm)
```
## Output:
### 1-Norm of a Matrix
<br>
<img width="566" height="203" alt="image" src="https://github.com/user-attachments/assets/f403e31c-5888-4c39-9784-81a4a1cb3793" />

<br>
<br>

### 2-Norm of a Matrix
<br>
<img width="513" height="245" alt="image" src="https://github.com/user-attachments/assets/720a9a42-3990-45cd-958e-ecbaa31bbfaa" />

<br>
<br>

### Infinity Norm of a Matrix
<br>
<img width="550" height="202" alt="image" src="https://github.com/user-attachments/assets/e63aaeea-3ee5-4cc4-bcdb-3bd51d3902fc" />

<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
