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
# Register No:23006090
# Developed By:pochireddy.p
# 1-Norm of a Matrix
```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```





# 2-Norm of a Matrix
```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

```



# Infinity Norm of a Matrix

```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

```



```
## Output:
### 1-Norm of a Matrix

![image](https://github.com/pochireddyp/Norm-of-a-matrix/assets/150232043/b478d451-516a-415e-be50-64715301b31f)

### 2-Norm of a Matrix

![image](https://github.com/pochireddyp/Norm-of-a-matrix/assets/150232043/13f8b492-09d5-445c-a874-ff03a4898913)

### Infinity Norm of a Matrix

![image](https://github.com/pochireddyp/Norm-of-a-matrix/assets/150232043/54f96d67-e27f-41f7-b39d-9c9063e68548)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
