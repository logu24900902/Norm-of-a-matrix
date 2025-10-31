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
# Developed By: 212224230141
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
<img width="626" height="209" alt="image" src="https://github.com/user-attachments/assets/81da6e23-666e-429b-95c6-024348de1a24" />

<br>
<br>

### 2-Norm of a Matrix
<br>
<img width="534" height="240" alt="image" src="https://github.com/user-attachments/assets/37259dff-c98f-4452-bb04-e597814d444c" />

<br>
<br>

### Infinity Norm of a Matrix
<br>
<img width="572" height="205" alt="image" src="https://github.com/user-attachments/assets/9ba3c515-aa98-4deb-8930-b04a1eaaf499" />

<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
