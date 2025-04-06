# Assignment - 2
---

# Task 1: Check if a Number is Even or Odd
---

# Code
```
a = int(input('Enter a number: '))
# Prompts the user to enter a number and converts the input from a string to an integer.

if (a % 2 != 0):
# Checks if the number is not divisible by 2 (i.e., remainder is not 0). If true, it's an odd number.

print(a, 'is an odd number.')
# Prints the result if the number is odd.

else:
# If the number is divisible by 2, this block runs.

print(a, 'is an even number.')
# Prints the result if the number is even.
```
# Sample output:
---
```
Enter a number: 9
9 is an odd number.
```

# Task 2: Sum of Integers from 1 to 50 Using a Loop
---
# Code
```
a = 0
# This initializes a variable a to store the total sum.

for i in range(1, 51):
# This loop goes from 1 to 50 (51 is not included).

a += i
# Adds each number i to a.

print('The sum of numbers from 1 to 50 is:', a)
# After the loop ends, it prints the total sum
```
# Sample output:
---
```
The sum of numbers from 1 to 50 is: 1275
