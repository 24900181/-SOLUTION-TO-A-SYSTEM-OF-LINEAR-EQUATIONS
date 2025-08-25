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
~~~
#Developed by: NETHRA.K
#Register Number: 212224230184


import numpy as np
A = np.array([[1,-3],[3,1]])
B = np.array([0,10])
le = np.linalg.solve(A,B)
print(le)
~~~

## Output:

<img width="1884" height="1031" alt="image" src="https://github.com/user-attachments/assets/8819b0f1-b74b-4dc3-8e93-3d615d1cf55a" />

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

