# Find the square root of a number

## AIM:
To write a program to find the square root of a number.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function.
2. Assign number_iters = 100 in the function to perform 100 iteratios.
3. Set i = 0.
4. Calculate  number = 0.5 * (number + a / number) for 100 iterations.
5. Return number

## Program:
```
/*
Program to find the square root for the given number(newton's method) using function.
Developed by: Karthikeyan R
RegisterNumber:  212222240045

def newton(n,n_iter =100):
    a=float(n)
    for i in range(n_iter):
        n=0.5*(n+a/n)
    return n
    
x=int(input())
print("Square root of the number:",newton(x))
*/
```

## Output:

![Screenshot 2023-06-03 111226](https://github.com/Yamunaasri/Square-root-of-a-number/assets/115707860/c50983a5-354a-453f-b6c2-d2a6adbb6392)


## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
