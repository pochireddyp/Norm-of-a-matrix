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

![Screenshot 2023-12-25 203230](https://github.com/pochireddyp/Norm-of-a-matrix/assets/150232043/a7206185-41f1-4cf3-ab9b-dd970f35365d)

### 2-Norm of a Matrix

![Screenshot 2023-12-25 203329](https://github.com/pochireddyp/Norm-of-a-matrix/assets/150232043/689582ec-13f2-4df1-996c-2beedcf0d8f2)

### Infinity Norm of a Matrix

![Screenshot 2023-12-25 203413](https://github.com/pochireddyp/Norm-of-a-matrix/assets/150232043/6d48d2f0-a39a-413c-9c37-7c0c7afc9d90)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
