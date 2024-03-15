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
#Developed by: sivakumar\n
#RegisterNumber:23013501\n
import numpy as np\n
A=[[1,3],[2,5]]\n
b=np.array ([5,-3])\n
c=np.linalg.solve(A,b)\n
print(c)

## Output:
<img width="558" alt="Screenshot 2024-03-15 081150" src="https://github.com/SIVAmech123/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/151629067/70ec713c-33f7-4cb8-83f9-a8dd93458f90">
<img width="440" alt="Screenshot 2024-03-15 081202" src="https://github.com/SIVAmech123/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/151629067/2fca5521-07f4-42da-8225-14fa4e18bd21">

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

