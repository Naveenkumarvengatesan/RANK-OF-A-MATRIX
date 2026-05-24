# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:

Step 1: Import the numpy module to use the built-in functions for calculation

Step 2: Prepare the lists from each equation and assign in np.array

Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.

Step 4: end the program

## Program:
~~~
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy as np

# Given matrix
matrix = [[5, -3, -10],
          [2, 2, -3],
          [-3, -1, 5]]

# Find rank of matrix
rank = np.linalg.matrix_rank(matrix)

# Print result
print(rank)
~~~

## Output:
<img width="629" height="823" alt="Screenshot 2026-05-24 224809" src="https://github.com/user-attachments/assets/da909189-43a7-436f-9a15-648dc6c78e39" />



## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

