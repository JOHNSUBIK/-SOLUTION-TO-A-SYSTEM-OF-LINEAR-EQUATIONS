# -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
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
#Developed by: John Paul J
#RegisterNumber:23011778
import numpy as np
A=[[1,-3],[3,1]]
B=[0,10]
C=np.linalg.solve(A,B)
print(C)
```

## Output:

![Screenshot 2023-11-25 235815](https://github.com/JOHNSUBIK/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/150279319/976702d6-f2d3-49a0-9584-b902df0d60a3)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

