# Find the square root of a number

## AIM:
To write a program to find the square root of a number.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
## Step 1:
Define a function.

## Step 2:
Assign number_iters = 100 in the function to perform 100 iteratios.

## Step 3:
Set i = 0.

## Step 4:
Calculate number = 0.5 * (number + a / number) for 100 iterations.

## Step 5:
Return number

## Program
```
Program to find the square root for the given number(newton's method) using function.
Developed by: R.karthikeyan 
RegisterNumber: 212222240045

def newton_method(number,number_iters=100):
     a=float(number)
     for i in range(number_iters):
         number=0.5*(number+a/number)
     return number
a=int(input())
print("Square root of the number:",newton_method(a))
```
## Output:

![image](https://github.com/karthikeyan-R16/Square-root-of-a-number/assets/119421232/1bad016d-5501-42e5-9b5b-7449468fe515)



## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
