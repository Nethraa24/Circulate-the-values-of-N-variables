# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
First step is to define the function
### Step 2: 
Get a,n inputs from the user
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5: 
Print the result

## Program:
```python
Developed by: J.Nethraa
Reference no.: 22006789
def circulate():
    a=eval(input())
    n=int(input())
    l=a[n:]+a[:n]
    print("After circulating the values are:",l)
```

## Output:
![image](https://user-images.githubusercontent.com/121215786/214862472-09ce1f21-f2de-428f-885a-8a8b81759843.png)

## Result:
Thus,n variables were circulated using function concept
