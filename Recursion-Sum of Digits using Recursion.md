# 7c)  Recursion:Sum of cube of Digits using Recursion in Python

##  AIM:
To write a Python program to calculate the **sum of cube of all digits** in a number using **recursion**.

##  ALGORITHM:

1.Start

2.Input an integer num.

3.Call the function sum_digits(num).

4.Inside sum_digits(num):

    If num < 0 or num is not an integer (i.e., int(num) != num),
    → Return 0

    Else if num == 0,
    → Return 0

    Else
      a. Compute the last digit → num % 10
      b. Cube the digit → (num % 10)³
      c. Call the function again with the remaining digits → sum_digits(num // 10)
      d. Return the sum of the cube of the last digit and the recursive result

5.Print the returned value.

6.End

##  PROGRAM:
```
def sum_digits(num):
    if num < 0 or int(num) != num:
        return 0
    elif num == 0:
        return 0
    else:
        return ((num % 10)**3) + sum_digits(num//10)
num= int(input())
print(sum_digits(num))
```
## OUTPUT
<img width="417" height="262" alt="image" src="https://github.com/user-attachments/assets/37212003-2b71-4a8e-a671-305750de5d15" />

## RESULT
Program executed Successfully.
