# Multiplying-two-matrix

## AIM:
To find the Multiplying-two-matrix
## ALGORITHM:

### Step 1:
Start the program
### Step 2:
Enter the row and column of the first matrix
### Step 3:
Enter the row and column of the second matrix
### Step 4:
Enter the elements of the first matrix
### Step 5:
Enter the elements of the second matrix
## PROGRAM: 

import numpy as np
l1,l2=[],[]
n=int(input())
for i in range(n):
    l1.append(int(input()))
for j in range(n):
    l2.append(int(input()))
array_1=np.array(l1)
array_2=np.array(l2)
product=array_1*array_2
print('Product of two arrays is:',product)

## OUTPUT:

![GitHub Logo](/image.png)

## RESULT:
Thus the multiplying-two-matrix is implemented using the python programming
