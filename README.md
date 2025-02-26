# DISTANCE-BETWEEN-TWO-POINTS

## AIM:
To write a python program to find the distance two 2 points
## ALGORITHM:
Step 1:

First, we import the "math" module, which provides various mathematical functions.

Step 2:

Then, we create two lists l1 and l2, each containing two values (x and y coordinates).

Step 3:

We use the "math.sqrt()" function to calculate the distance between the two points, which is the square root of the sum of the squares of the differences in the x and y coordinates.

Step 4:

We assign the result of the calculation to the variable "distance".

Step 5:

Finally, we use the "print()" function to display the value of "distance" with two decimal places.

Step 6:

The program ends after printing the distance.

### PROGRAM:
```
#Program to find the distance between two points.
#Developed by: NAVEEN KUMAR M
#RegisterNumber: 212222110028
import math
l2=[10,6]
l1=[4,2]
distance=math.sqrt(((l2[0]-l1[0])**2)+((l2[1]-l1[1])**2))
print("{:.2f}".format(distance))

```


### OUTPUT:
![image](https://user-images.githubusercontent.com/119394582/234815887-297d4449-288d-424c-b96e-30bb4eaf0d7a.png)


### RESULT:
Program to find the distance between two points was successfully executed.
