# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Create a function to rotate a list of elements
### Step 2: 
Define a list of n elements
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list

### Step 5:
Print the result list the values would be circulated according to the number of rotation value given by the user
### Step 6: 
End the program

## Program:
```
#Program to circulate N values.

#Developed by: GAUTHAM M G

#RegisterNumber:21000182

def circulate():

    l=[10,20,30,40,50,60]
    
    n=int(input())
    
    result=l[n:]+l[:n]
    
    print("After circulating the values are:",result)
    
```
## Output:

![image](https://user-images.githubusercontent.com/94810884/152166518-aabde4ef-bb82-41d7-8cb4-f94550689d73.png)


## Result:
Thus the circulation of n variables using function concept are successfully executed.
