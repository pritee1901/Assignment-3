#task 1:
'''
Calculate Factorial Using a Function


Problem Statement: Write a Python program that:
1.   Defines a function named factorial that takes a number as an argument and calculates its factorial using a loop or recursion.
2.   Returns the calculated factorial.
3.   Calls the function with a sample number and prints the output.
'''

#task 1:
def factorial(n):
    result=1
    for i in range(1,n+1):
        result*=i
    return result
num=int(input("Enter a number: "))
print(f"factorial of{num} is:{factorial(num)}")
'''


#task 2:
import math
num=float(input("Enter a number: "))
sqrt_val=math.sqrt(num)
log_val=math.log(num)
sine_val=math.sin(num)

print(f"square root of {num} is:{sqrt_val}")
print(f"logarithm of {num} is:{log_val}")
print(f"sine of {num} is:{sine_val}")
