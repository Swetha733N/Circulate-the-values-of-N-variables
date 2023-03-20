# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Get the list of values from the user
### Step 2: 
Get the input from the user
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list

### Step 5: 
Execute the code
### Step 6: 
End the program.
## Program:
```
#Program to circulate N values.
#Developed by:N.Swetha
#RegisterNumber:212222110050
def circulate():
    list1=eval(input())
    n=int(input())
    result=list1[n:]+list1[:n]
    print("After circulating the values are:",result)
```

## Output:
![output](./circulatenvalues.png)

## Result:
The program for circulating n variables is executed successfully
