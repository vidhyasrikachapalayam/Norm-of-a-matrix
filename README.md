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

# Register No:22008468

# Developed By:vidhyasri.k

# 1-Norm of a Matrix

import numpy as np

mat=np.array(eval(input()))

ans=np.linalg.norm(mat,1)

norm_of_matrix="{:.2f}".format(ans)

print(norm_of_matrix)


# 2-Norm of a Matrix

import numpy as np

mat = np.array(eval(input()))

ans = np.linalg.norm(mat,2)

Norm_of_matrix = "{:.2f}".format(ans)

print(Norm_of_matrix)



# Infinity Norm of a Matrix
import numpy as np

mat = np.array(eval(input()))

ans = np.linalg.norm(mat,np.inf)

Norm_of_matrix = "{:.2f}".format(ans)

print(Norm_of_matrix)






## Output:
### 1-Norm of a Matrix
![norm1](https://user-images.githubusercontent.com/119477817/215282612-ea0728c1-66c2-4bbd-a173-32c689ca0560.png)



### 2-Norm of a Matrix

![norm2](https://user-images.githubusercontent.com/119477817/215282625-f01418e1-f313-4a84-b1fd-46004f0fa0d4.png)




### Infinity Norm of a Matrix

![norm3](https://user-images.githubusercontent.com/119477817/215282646-d720c90e-dd85-4196-aa9e-b48e847b3cfd.png)



## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
