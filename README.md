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
# Register No:25018207
# Developed By:VIGNESH.K

```
import numpy as np
a=np.array(eval(input()))
norm=np.linalg.norm(a,1)
print(norm)
```
```
import numpy as np
a=np.array(eval(input()))
n=np.linalg.norm(a,2)
print("{:.2f}".format(n))
```
```
import numpy as np
a=np.array(eval(input()))
n=np.linalg.norm(a,np.inf)
print(n)
```
```
## Output:
### 1-Norm of a Matrix

<img width="1239" height="239" alt="Screenshot 2025-12-18 235128" src="https://github.com/user-attachments/assets/c59e0561-a507-41ed-a1bf-2b81d3b9f6b9" />

### 2-Norm of a Matrix

<img width="1230" height="278" alt="Screenshot 2025-12-18 235904" src="https://github.com/user-attachments/assets/b9bcf7e4-3ead-493b-bd8b-5c0fa8e2d6fb" />

### Infinity Norm of a Matrix

<img width="1245" height="235" alt="Screenshot 2025-12-19 000007" src="https://github.com/user-attachments/assets/23053e5c-30ad-4d67-af31-db0579741da6" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
