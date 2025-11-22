# 7d)  Taylor Series Using Recursion in Python

##  AIM:
To write a Python program to evaluate a **Taylor Series** using **recursion**, where values of `x` and `n` are taken from the user.

##  ALGORITHM:

1. **Start**
2. Create variables `x` and `n`
3. Get values for `x` and `n` from the user
4. Define a recursive function `series(x, n)`
   - **Base case:** If `n == 0`, return 1
   - **Recursive case:** Return `x**n / n + series(x, n-1)`
5. Print the result
6. **Stop**

##  PROGRAM:
```
def func(x, n):
    if n == 0:
        return 1
    return (3 ** n)*(x**n) + func(x, n - 1)

x = int(input())
n = int(input())
print(func(x, n))
```

## OUTPUT
<img width="383" height="258" alt="image" src="https://github.com/user-attachments/assets/a01191c2-a231-4aad-a441-b1b8547965b7" />

## RESULT
Program executed Successfully.
