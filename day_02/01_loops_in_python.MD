# Loops in Python

## Introduction
Loops are used in programming to repeat a specific block of code. In Python, there are two main types of loops:
- `for` loops
- `while` loops

## `for` Loop
The `for` loop in Python is used to iterate over a sequence (such as a list, tuple, dictionary, set, or string).

### Syntax
```python
for variable in sequence:
    # code block to be executed
```

### Example
```python
fruits = ["apple", "banana", "cherry"]
for fruit in fruits:
    print(fruit)
```

### Explanation
In this example, the `for` loop iterates over each item in the `fruits` list and prints it.

## `while` Loop
The `while` loop in Python is used to execute a block of code as long as a condition is true.

### Syntax
```python
while condition:
    # code block to be executed
```

### Example
```python
count = 0
while count < 5:
    print(count)
    count += 1
```

### Explanation
In this example, the `while` loop continues to execute as long as `count` is less than 5. The `count` variable is incremented by 1 in each iteration.

## Conclusion
Loops are fundamental in Python for performing repetitive tasks efficiently. The `for` loop is ideal for iterating over sequences, while the `while` loop is suitable for scenarios where the number of iterations is not known in advance.


## Interview Questions

1. **What is the difference between a `for` loop and a `while` loop in Python?**
    - A `for` loop is used for iterating over a sequence (like a list, tuple, dictionary, set, or string), while a `while` loop is used to execute a block of code as long as a condition is true.

2. **Can you break out of a loop in Python? If so, how?**
    - Yes, you can use the `break` statement to exit a loop prematurely.

3. **How can you skip the current iteration of a loop in Python?**
    - You can use the `continue` statement to skip the current iteration and move to the next iteration of the loop.

4. **What is an infinite loop? How can you create one using a `while` loop?**
    - An infinite loop is a loop that runs indefinitely because the condition always evaluates to true. You can create one using a `while` loop with a condition that always evaluates to true, such as `while True:`.

5. **How can you iterate over a dictionary using a `for` loop?**
    - You can iterate over a dictionary using a `for` loop by iterating over its keys, values, or key-value pairs using methods like `.keys()`, `.values()`, or `.items()`.

6. **What is the `else` clause in a loop, and when does it execute?**
    - The `else` clause in a loop executes after the loop completes normally (without encountering a `break` statement).

7. **Can you nest loops in Python? Provide an example.**
    - Yes, you can nest loops in Python. For example:
      ```python
      for i in range(3):
            for j in range(2):
                 print(i, j)
      ```

8. **What is the purpose of the `pass` statement in a loop?**
    - The `pass` statement is a null operation; it is used as a placeholder in loops (or other control structures) where code is syntactically required but you do not want to execute any code.
