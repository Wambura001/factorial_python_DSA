# factorial_python_DSA

## Single Best Case

### Code

def factorial(n):
if n == 0:
return 1
else:
return n * factorial(n - 1)

x = 5
print(&quot;\n Factorial of &quot;, x, &quot; is &quot;, factorial(x))

### Output
Factorial of 5 is 120

### Explanation:
Explanation:
Base Case: If n==0 , the function returns 0 .For all other values, the function recurses summing the
current number n and the result of the function called with n - 1.

## 2 Best Cases

### Code

def factorial_2(n):
if n == 0:
return 0
elif n == 1:
return 1
else:
return n + factorial_2(n - 1)

x = 5
print(&quot;\n Factorial of &quot;, x, &quot; is &quot;,factorial_2(x))

### Output
Factorial of 5 is 15

### Explanation:
Base Case 1: If n == 0 , the function returns 0 .Base Case 2: If n == 1 , the function returns 1 or any
other value of n , the function recurses, summing the current number n and the result of the
function called with n -1. This approach ensures that the recursion ends even if n is very small, as
the two base cases cover the smallest possible values of n == 0 and n == 1.
