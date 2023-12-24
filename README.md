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
Developed by: 
RegisterNumber:  
*/
n=int(input())
approx=0.5*n
for i in range(1,10):
    a=0.5*(approx+n/approx)
    approx=a
print("Square root of the number:",a)

```

## Output:
![Screenshot 2023-12-24 195949](https://github.com/nainamohamed09642/Square-root-of-a-number/assets/151916360/519aada3-e54d-42e7-b68f-c124a469ffe9)




## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
