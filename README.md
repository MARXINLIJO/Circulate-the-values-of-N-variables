# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 

Step 1:
first step is to define the function

Step 2:
get a,n inputs from the user

Step 3:
define the formula

Step 4:
Get the value from the user for the number of rotation

Step 5:
Using the slicing concept rotate the list

Step 6:
print the result
## Program:
```
#Program to circulate N values.
#Developed by: Marxin Lijo
#RegisterNumber:23013468
def circulate():
    a=eval(input())
    n=int(input())
    a=a[n: ]+a[ :n]
    print("After circulating the values are:",a);
```
## Output:
![image](https://github.com/MARXINLIJO/Circulate-the-values-of-N-variables/assets/145742540/8aee7dae-9fb5-46d2-a824-169f13588133)

## Result:
The program executed sucessfully.
