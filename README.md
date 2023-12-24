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
#Program to find the solution for the given linear equations.
#Developed by: DHARSANKUMAR R
#RegisterNumber:23014208
import numpy as np
a=[[1,3],[2,5]]
b=np.array([5,-3])
c=np.linalg.solve(a,b)
print(c)
~~~

## Output:
![image](https://github.com/DHARSAN23014208/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/149365413/e6a4bdb3-9124-40b6-94a1-48ce787c7dc3)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

