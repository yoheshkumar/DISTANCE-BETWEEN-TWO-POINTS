# DISTANCE-BETWEEN-TWO-POINTS

## AIM:
To write a python program to find the distance two 2 points
## ALGORITHM:
### Step 1: 
Import the math module to use the built-in functions for calculation
### Step 2: 
take two lists containing the points as the element
### Step 3: 
Substitute the values in the distance formula 

  ![formula](./formula.JPG)
### Step 4: 
print the distance with two decimal places
### Step 5:
end the program
### PROGRAM:
```
#Program to find the distance between two points.
#Developed by: Yohesh Kumar R.M
#RegisterNumber:22008459
import math
a=[4,2]
b=[10,6]
dist=math.sqrt(((b[0]-a[0])**2)+((b[1]-a[1])**2))
print("{:.2f}".format(dist))
```


### OUTPUT:
![output](op3.png)

### RESULT:
This program is executed sucessfully
