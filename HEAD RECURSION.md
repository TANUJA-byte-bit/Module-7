# Module 7
# 7a)  Types of Recursion: Head Recursion in Python

##  AIM:
To write a Python program to print even numbers till ‘N’ using head recursion.


##  ALGORITHM:

1.Read an integer a from the user.

2.Call the function fun(a, 2).

3.Inside the function fun(a, c):

   Check if c ≤ a.

   If true:

   Print c with a space.

   Recursively call fun(a, c + 2).

4.The recursion stops when c > a.

5.End.

##  PROGRAM:
```
def fun(a,c=2):
    if c<=a:
        print(c,end=' ')
        fun(a,c+2)
 
a = int(input())
fun(a)
```
## OUTPUT
<img width="1018" height="257" alt="image" src="https://github.com/user-attachments/assets/aa07f8e5-ba5b-40f8-8bd5-97b4291ecfae" />

## RESULT
Program executed Successfully.
