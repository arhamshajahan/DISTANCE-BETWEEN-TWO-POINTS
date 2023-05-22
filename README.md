# DISTANCE-BETWEEN-TWO-POINTS

## AIM:
To write a python program to find the distance two 2 points
## ALGORITHM:
### Step 1: 
### Step 2: 
### Step 3: 
Substitute the values in the distance formula  ![formula](/formula.JPG)
### Step 4: 
### Step 5: 
### PROGRAM:
#Program to find the distance between two points.
#Developed by:ARHAM S 
#RegisterNumber:212222110005
import math
def distance_between_points(x1,y1,x2,y2):
    dx = x2-x1
    dy = y2 -y1
    distance = math.sqrt(dx**2 + dy**2)
    return distance
    
if __name__=="__main__":
     distance = distance_between_points(10,6,4,2)
     print("{:.2f}".format(distance))



### OUTPUT:
![Screenshot (14)2](https://github.com/arhamshajahan/DISTANCE-BETWEEN-TWO-POINTS/assets/127313881/ed15e36c-1777-41b3-8dc0-5e64ee7fbdd0)


### RESULT:
the distance between the two points are succesfully found.
