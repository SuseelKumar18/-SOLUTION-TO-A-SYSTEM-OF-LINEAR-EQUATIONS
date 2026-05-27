# -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
## Aim:
To write a python program to find a solution to a system of linear equations.
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:

1. Import the NumPy library.
2. Define the coefficient matrix A.
3. Define the constant matrix B.
4. Use np.linalg.solve() function to solve the equations.
5. Display the values of x, y, and z.

### Step 1: 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.solve(), we can find the solutions.
### Step 4: 
End the program
## Program:

# Program to solve a system of linear equations
# Using NumPy library

import numpy as np

# Coefficient matrix
A = np.array([[2, 3, -1],
              [1, -2, 4],
              [3, 1, 2]])

# Constant matrix
B = np.array([5, 8, 7])

# Finding solution
solution = np.linalg.solve(A, B)

# Display result
print("Solution of the system of equations:")
print("x =", solution[0])
print("y =", solution[1])
print("z =", solution[2])

## Output:

Solution of the system of equations:
x = 2.52
y = 0.65
z = 1.95

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

