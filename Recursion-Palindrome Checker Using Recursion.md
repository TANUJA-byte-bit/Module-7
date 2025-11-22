# 7b)  Recursion: Factorial of number
##  AIM:
To write a Python program to find the result of a! + b! using recursion

---

##  ALGORITHM:
1.Start.

2.Read the value of a from the user.

3.Read the value of b from the user.

4.Define a function factorial(n):

     If n = 0, return 1.
  
     Otherwise, return n × factorial(n−1).

5.Compute factorial(a) and factorial(b).

6.Add the two factorial values and store the result in sum.

7.Print sum.

8.End.

##  PROGRAM:
```
def factorial(n):
    if(n==0):
      return 1
    return(n *factorial(n-1))
 
a=int(input())
b=int(input())
sum=factorial(a)+ factorial(b)
print(sum)
```
## OUTPUT
<img width="482" height="309" alt="image" src="https://github.com/user-attachments/assets/57b0d3bb-3804-4af2-8c3c-345de92dd7b1" />

## RESULT
Program executed Successfully.
