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
# Register No:22004659
# Developed By:Prithviraj.V
# 1-Norm of a Matrix

import numpy as np

mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
norm_of_matrix = "{:.2f}".format(ans)
print(norm_of_matrix)


# 2-Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
norm_of_matrix = "{:.2f}".format(ans)
print(norm_of_matrix)



# Infinity Norm of a Matrix
import numpy as np
mat= np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)




```
## Output:
![norm of a matrix](https://user-images.githubusercontent.com/121418418/214922093-92330688-80ff-4fde-b042-2ec6eb01e408.png)
![norm of a matrix(2)](https://user-images.githubusercontent.com/121418418/214922232-8540c189-e4dc-43d1-a80d-27664779b3df.png)
![norm of a matrix(2)](https://user-images.githubusercontent.com/121418418/214922314-c4448881-1645-4db4-a2ab-2dab5590fd8e.png)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
