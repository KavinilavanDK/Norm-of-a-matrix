## DATE:
## EXNO 07: Norm of a matrix
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

### Register No:212223230103
### Developed By:KAVI NILAVAN DK
## 1-Norm of a Matrix
```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_mat="{:.2f}".format(ans)
print(norm_of_mat)
```


## 2-Norm of a Matrix
```
import numpy as np
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_mat="{:.2f}".format(ans)
print(norm_of_mat)
```



## Infinity Norm of a Matrix

```

import numpy as np
mat=np.array(eval(input()))

norm=np.linalg.norm(mat,ord=np.inf)
print("{:.2f}".format(norm))

```
## Output:
### 1-Norm of a Matrix

![Screenshot 2024-10-23 185521](https://github.com/user-attachments/assets/703fc66f-dd7f-4817-a66b-bc2a1a2c3588)

### 2-Norm of a Matrix

![Screenshot 2024-10-23 185537](https://github.com/user-attachments/assets/9f5bbb8e-3226-4822-b965-9a4bd1c28df4)

### Infinity Norm of a Matrix

![Screenshot 2024-10-23 185553](https://github.com/user-attachments/assets/d2fba51f-fab9-4e33-88a9-2153c4f85f0e)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
