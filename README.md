# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
create a function to circulate the variables
### Step 2: 
Initialize a list from the user using eval
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list

### Step 5:
we do this initializing a variable 1 and adding the values before index and after the index in the list
### Step 6: 
print the value of 1
## Program:
```python
###Program to circulate N values.
###Developed by:JEECIKASRINA M
###RegisterNumber:23013947
def circulate():
    l=eval(input())
    n=int(input())
    l=l[n:]+l[:n]
    print("After circulating the values are:",l)
```
## Output:
![image](https://github.com/Jeecikasrina23013947/Circulate-the-values-of-N-variables/assets/148515300/aa50724a-7e25-444b-9cb2-03298473fbf7)

## Result:
