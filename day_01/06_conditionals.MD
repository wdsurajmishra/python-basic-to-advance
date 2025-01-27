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