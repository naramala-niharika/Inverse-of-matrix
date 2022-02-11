# Inverse-of-matrix

## AIM:
To write a python program to find inverse of a matrix

## ALGORITHM:

### Step 1:
use import as np
### Step 2:
Enter the input.
### Step 3:
Use for loop and range.
### Step 4:
Use np.linalg.inv() to find inver of a matrix.
### Step 5:
Print()

## PROGRAM:

Developed By: N.Niharika

Reference no:21500912

import numpy as np

l1,l2=[],[]

r=int(input())

c=int(input())

for i in range (r):

    for j in range (c):

        num=int(input())
        l1.append(num)
    l2.append(l1)
    l1=[]
print(l2)

value1=np.array(l2)

inverse=np.linalg.inv(value1)

print(inverse)

## OUTPUT:
![output]()

## RESULT:
