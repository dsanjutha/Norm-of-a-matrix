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
# Register No:212225240136
# Developed By:D.sanjutha
# 1-Norm of a Matrix
import numpy as np
A=np.array(eval(input()))
norm1=np.linalg.norm(A,1)
print(f"{norm1:.2f}")

# 2-Norm of a Matrix
import numpy as np
A=np.array(eval(input()))
norm2=np.linalg.norm(A,2)
print(f"{norm2:.2f}")

# Infinity Norm of a Matrix
import numpy as np
A=np.array(eval(input()))
result=np.linalg.norm(A,np.inf)
print(f"{result:.2f}")
```
## Output:
### 1-Norm of a Matrix

<img width="1018" height="762" alt="Screenshot 2026-02-25 170607" src="https://github.com/user-attachments/assets/a61075b6-098e-4544-a2ed-4f3fe3b9c9f7" />

### 2-Norm of a Matrix

<img width="859" height="804" alt="Screenshot 2026-02-25 170652" src="https://github.com/user-attachments/assets/b98a1452-d266-4f5e-b52a-b778c35b82c8" />

### Infinity Norm of a Matrix

<img width="724" height="785" alt="Screenshot 2026-02-25 170731" src="https://github.com/user-attachments/assets/4cc20047-c472-46a4-80df-70e9f86abb87" />

## Result

Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
