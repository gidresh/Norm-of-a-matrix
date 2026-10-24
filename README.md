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
# Register No:26019128
# Developed By:idrish
# 1-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A=np.array(eval(input()))
norm1=np.linalg.norm(A,1)
norm="{:.2f}".format(norm1)
print(norm)



# 2-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A=np.array(eval(input()))
norm2=np.linalg.norm(A,2)
norm="{:.2f}".format(norm2)
print(norm)



# Infinity Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A=np.array(eval(input()))
norminf=np.linalg.norm(A,np.inf)
norm="{:.2f}".format(norminf)
print(norm)




```
## Output:
### 1-Norm of a Matrix
<img width="1199" height="740" alt="{A0314024-1815-4562-8758-CF3B214DF44F}" src="https://github.com/user-attachments/assets/b55b84a0-dfff-4d6e-a198-51dd848ce01a" />
<img width="1287" height="342" alt="{12F8836F-8E8F-4957-8943-8ECB1C71FE21}" src="https://github.com/user-attachments/assets/7f0ffd9e-086d-4b81-8f68-092069451319" />


### 2-Norm of a Matrix
<img width="1217" height="669" alt="{B9D0287F-AF2E-43DA-9067-0907F69A5F3B}" src="https://github.com/user-attachments/assets/edf0dd86-fdc1-4fb9-a33c-c78a1d225ca5" />
<img width="1312" height="376" alt="{5D9F6057-9127-4D98-9F68-0AC044231507}" src="https://github.com/user-attachments/assets/0e6362a4-75b6-45bd-8f6a-8d3a8b64e21b" />


### Infinity Norm of a Matrix
<img width="1210" height="630" alt="{1CE9C97E-02CD-4954-80E4-7D688908CEFF}" src="https://github.com/user-attachments/assets/f3524312-f231-485d-abf5-8fbecf05617c" />
<img width="1235" height="341" alt="{A0EEBF64-6576-4F1E-B029-9C2F3EB4FA9B}" src="https://github.com/user-attachments/assets/887ecbd6-1a08-4379-a46c-23c4d373ab90" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
