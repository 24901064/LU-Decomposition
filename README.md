# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
Algorithm 1:
1.Import numpy and scipy.linalg,in linalg you can input lu. and in second program can import lu_factor and lu_solve from python library as same as in second program.

2.Get the input from user as the form of nested list to compute numpy array format.

3.Use inputted array (matrix) to compute in corresponding builtin modules function such as lu and create new variables such as piv,i matrix u matrix to store.

4.Print the corresponding bvariable to get output (I_matrix)

5.Print the corresponding bvariable to get output (u_matrix)

Algorithm 2:
1.In second program can import lu_factor and lu_solve from python library as same as in second program.

2.Get the input from user in the form of nested list to compute numpy array format and declare it for both the variables.

3.Create the varaiable to Use inputted array to compute of lu_factor of matrix varaible.

4.Create the new variable for lu_solve to compute of 'x' varaiable and 'b' variable.

5.Print the corresponding variable (solution) to get output.


## Program:
(i) To find the L and U matrix
```
/*import numpy as np 
from scipy.linalg import lu 
matrix=np.array(eval(input()))
piv,l_matrix,u_matrix=lu(matrix)
print(l_matrix)
print(u_matrix)
Program to find the L and U matrix.
Developed by: BHARANI KUMAR.S
RegisterNumber: 212224230035
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*import numpy as np
from scipy.linalg import lu_factor,lu_solve
matrix=np.array(eval(input()))
b=np.array(eval(input()))
x=lu_factor(matrix)
solution=lu_solve(x,b)
print(solution)
Program to find the LU Decomposition of a matrix.
Developed by: BHARANI KUMAR.S
RegisterNumber: 212224230035
*/
```

## Output:
![Screenshot 2025-04-12 140908](https://github.com/user-attachments/assets/311d2b26-f9ea-4434-a896-b4b6e2bbcc28)
![Screenshot 2025-04-12 140920](https://github.com/user-attachments/assets/7ed25e9d-baf1-4714-9e76-0873a3dc26b3)




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

