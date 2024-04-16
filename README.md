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
Developed by: kishore N
RegisterNumber:212223230106  
*/
def sqrt(x):
    if x<0:
        print("not defined")
    y=x/2.0
    while True:
        new=0.5*(y+x/y)
        if new==y:
            break
        y=new
    return y
num=int(input())
res=sqrt(num)
print(f"Square root of the number: {res}")
```

## Output:

![Screenshot 2024-04-16 215321](https://github.com/kishorenagarajan08/Square-root-of-a-number/assets/155753188/2569d7bf-6971-429e-8ffa-e2af22b18771)


## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
