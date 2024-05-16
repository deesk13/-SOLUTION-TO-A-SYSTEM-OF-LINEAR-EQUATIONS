# -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
NAME : DEVA DHARSHINI I

REGISTER NO: 212223240026

DEPARTMENT: AIML
## Aim:
To write a python program to find a solution to a system of linear equations.
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import the numpy module to use the built-in functions for calculation 
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.solve(), we can find the solutions.
### Step 4: 
End the program
## Program:
```
#Program to find the solution for the given linear equations.
#Developed by: Deva Dharshini I
#RegisterNumber: 212223240026
import numpy as np
a = np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
b = np.array([-9,4,-1])
solution=np.linalg.solve(a,b)
print(solution)
```

## Output:
![Screenshot 2024-04-10 214834](https://github.com/deesk13/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/150927063/a553deca-0399-49a8-8c4c-9a3f21261e9c)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

