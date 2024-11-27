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
import numpy as x
a=x.array([[1, -3], [3, 1]])
b=x.array([0, 10])
c=x.linalg.solve(a, b)
print(c)

```
## Output:

<img width="946" alt="Screenshot 2024-11-27 at 09 43 06" src="https://github.com/user-attachments/assets/70b8891e-ea9f-4d60-ad3a-776ba79c067c">

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

