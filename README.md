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
# Register No:212224110033
# Developed By:M krishna kumaran
````
```
# 1-Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)
```
```
# 2-Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)
```
```
# Infinity Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
print("{:.2f}".format(ans))
```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/user-attachments/assets/e9b8c500-1b56-4958-ad14-2b9fa7294ad7)


### 2-Norm of a Matrix
![image](https://github.com/user-attachments/assets/57ffe39b-f192-40c2-9e15-a1ed439f3d64)

### Infinity Norm of a Matrix
![image](https://github.com/user-attachments/assets/991a74c7-d500-468a-873c-0d56a82ef81c)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
