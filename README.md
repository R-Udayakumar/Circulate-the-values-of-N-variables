# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Create a function
### Step 2: 
Get the list which need to be circulated
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
 
## Program:
```
#Program to circulate N values.
#Developed by: udayakumar R
#RegisterNumber: 22008609
def circulate():
    a=eval(input())    
    x=int(input())
    print("After circulating the values are: {}".format(a[x:]+a[:x]))
```

## Output:
![OUTPUT](output.png)

## Result:
Thus the circulate the values of N variables are successfully executed
