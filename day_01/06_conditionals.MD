# Conditional Logic in Python

Conditional logic is a fundamental concept in programming that allows you to execute certain pieces of code based on whether a condition is true or false. In Python, conditional statements are created using `if`, `elif`, and `else` keywords.

## Basic `if` Statement

The `if` statement evaluates a condition and executes the indented block of code if the condition is true.

```python
x = 10
if x > 5:
    print("x is greater than 5")
```

## `if`-`else` Statement

The `else` block is executed when the `if` condition is false.

```python
x = 3
if x > 5:
    print("x is greater than 5")
else:
    print("x is not greater than 5")
```

## `if`-`elif`-`else` Statement

The `elif` keyword stands for "else if" and allows you to check multiple conditions.

```python
x = 7
if x > 10:
    print("x is greater than 10")
elif x > 5:
    print("x is greater than 5 but less than or equal to 10")
else:
    print("x is 5 or less")
```

## Nested Conditionals

You can also nest conditional statements within each other.

```python
x = 8
if x > 5:
    if x % 2 == 0:
        print("x is greater than 5 and even")
    else:
        print("x is greater than 5 and odd")
else:
    print("x is 5 or less")
```

## Logical Operators

You can combine multiple conditions using logical operators like `and`, `or`, and `not`.

```python
x = 4
y = 10
if x > 2 and y > 5:
    print("Both conditions are true")
if x > 5 or y > 5:
    print("At least one condition is true")
if not x > 5:
    print("x is not greater than 5")
```

Understanding and using conditional logic effectively is crucial for controlling the flow of your programs and making decisions based on different conditions.

## Interview Questions

Here are some common interview questions related to conditional logic in Python:

1. **What is a conditional statement in Python?**
    - Explain the purpose of conditional statements and how they are used in Python.

2. **How does the `if` statement work in Python?**
    - Describe the syntax and provide an example of an `if` statement.

3. **What is the difference between `if`, `elif`, and `else`?**
    - Explain the use cases for each keyword and how they differ from each other.

4. **Can you nest `if` statements in Python?**
    - Provide an example of nested `if` statements and explain how they work.

5. **What are logical operators and how are they used in conditional statements?**
    - Discuss the `and`, `or`, and `not` operators with examples.

6. **How would you write a conditional statement to check multiple conditions?**
    - Demonstrate how to use logical operators to combine multiple conditions in a single `if` statement.

7. **What happens if none of the conditions in an `if`-`elif`-`else` chain are true?**
    - Explain the flow of execution when none of the conditions are met.

8. **Can you use conditional statements with non-boolean values?**
    - Discuss how Python evaluates non-boolean values in conditional statements.

9. **What is the importance of indentation in Python's conditional statements?**
    - Explain the role of indentation and what happens if it is not used correctly.

10. **How can you handle complex conditional logic in Python?**
     - Provide strategies for managing complex conditions, such as using functions or breaking down conditions into simpler parts.

These questions can help you prepare for interviews and deepen your understanding of conditional logic in Python.