## Solutions for Python Loop Exercises

### Exercise 1: Sum of Even Numbers

```python
# Write a Python program to find the sum of all even numbers between 1 and 50 using a for loop.

sum_even = 0
for num in range(2, 51, 2):  # Start from 2 to include even numbers, step by 2
    sum_even += num

print("Sum of even numbers between 1 and 50:", sum_even)
```

**Explanation:**
To find the sum of even numbers between 1 and 50, we iterate through all even numbers in the range using a for loop. We start from 2 (the first even number) and go up to 50 (inclusive), incrementing by 2 in each step. This ensures that we only consider even numbers. We add each even number to the variable `sum_even`, and finally, print the total sum.

### Exercise 2: Fibonacci Sequence

```python
# Create a program to generate the Fibonacci sequence up to the nth term using a for loop.

def fibonacci(n):
    fib_sequence = [0, 1]
    for i in range(2, n):
        fib_sequence.append(fib_sequence[i - 1] + fib_sequence[i - 2])
    return fib_sequence

n = int(input("Enter the number of terms: "))
fib_sequence = fibonacci(n)
print("Fibonacci sequence up to the", n, "term(s):", fib_sequence)
```

**Explanation:**
The Fibonacci sequence is a series of numbers where each number is the sum of the two preceding ones. We initialize the sequence with the first two terms, 0 and 1. Then, using a for loop, we calculate the subsequent terms by adding the last two terms. We repeat this process until we have generated the required number of terms specified by the user.

### Exercise 3: Palindrome Check

```python
# Implement a Python function to check if a given number is a palindrome using a while loop.

def is_palindrome(number):
    original_number = number
    reversed_number = 0
    while number > 0:
        digit = number % 10
        reversed_number = reversed_number * 10 + digit
        number //= 10
    return original_number == reversed_number

num = int(input("Enter a number: "))
if is_palindrome(num):
    print(num, "is a palindrome.")
else:
    print(num, "is not a palindrome.")
```

**Explanation:**
To check if a number is a palindrome, we reverse the number and compare it with the original number. We use a while loop to extract each digit of the number from the right (least significant digit) to the left (most significant digit). For each iteration, we extract the last digit using the modulus operator `%` and add it to the reversed number. Then, we remove the last digit from the original number by integer division `//`. After the loop, if the reversed number is equal to the original number, then the number is a palindrome.

