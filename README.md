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
#Program to find the solution for the given linear equations.
#Developed by: KISHORE NARAYANAN S R
#RegisterNumber:212223110023
import numpy as np
coefficients = np.array([[5,-3,-10], [2,2,-3], [-3,-1,5]])
constants = np.array([-9,4,-1])
solution = np.linalg.solve(coefficients, constants)
print(solution)


## Output:
![Screenshot 2024-04-15 131916](https://github.com/KISHORENARAYANANSR/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/148202102/8b65b3f8-a0fd-4bb2-950b-0d954ef8c8d8)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

