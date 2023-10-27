# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Get the two values from the user
### Step 2: 
In circular swapping, the value of the first variable is assigned to the second variable
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5: 
Print both the values it would be circulated
### Step 6: 
End the program
## Program:
```
# Program to circulate N values.
# Developed by:Gokkul.M
# RegisterNumber:23014201
def circulate():
   l=eval(input())
   n=int(input())
   l=l[n:]+l[:n]
   print("After circulating the values are:",l)
```

## Output:
![Screenshot 2023-10-20 122315](https://github.com/Gokkul-M/Circulate-the-values-of-N-variables/assets/144870543/55de856d-1b96-47b6-9ffb-d51dc7c0d56f)
![Screenshot 2023-10-20 122333](https://github.com/Gokkul-M/Circulate-the-values-of-N-variables/assets/144870543/a8bf4e66-65e7-4ce4-87e5-72e128a4fef3)

## Result:
Thus the Circulation of the values of N variables are successfully executed
