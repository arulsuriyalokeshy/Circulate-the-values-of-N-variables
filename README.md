# Circulate-the-values-of-N-variables
## Aim:
To write a python program tC function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
Create a function to Circulate the values of variables
### Step 1:
Create a function to Circulate the variables
### Step 2:
initialize a list from user using eval function
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5: 
We do this initializing a variable 1 and adding the values
before index in the list
### Step 6:
print the value of 1
## Program:
###Program to Circulate N values.
```Developed by Suriya prakash.S
   Register Number 23013599```
def circulate():
    l=eval(input())
    n=int(input())
    l=l[n:]+l[:n]
    print("After circulating the values are:",l)

## Output:
![image](https://github.com/arulsuriyalokeshy/Circulate-the-values-of-N-variables/assets/149130151/7d85cd69-5eff-4a07-84be-a8df727e1ded)


## Result:
The python program for Ciculate the values of N variable is execueted successful
