# Number Guessing Game in Python

This document provides a step-by-step guide to creating a simple number guessing game in Python.

## Requirements

- Python 3.x

## Game Description

The game will randomly select a number between 1 and 100, and the player will have to guess the number. The game will provide feedback on whether the guessed number is too high, too low, or correct.

## Implementation

### Step 1: Import Required Libraries

```python
import random
```

### Step 2: Define the Main Function

```python
def main():
    number_to_guess = random.randint(1, 100)
    attempts = 0
    guessed = False

    print("Welcome to the Number Guessing Game!")
    print("I have selected a number between 1 and 100. Can you guess it?")

    while not guessed:
        try:
            guess = int(input("Enter your guess: "))
            attempts += 1

            if guess < number_to_guess:
                print("Too low! Try again.")
            elif guess > number_to_guess:
                print("Too high! Try again.")
            else:
                guessed = True
                print(f"Congratulations! You've guessed the number in {attempts} attempts.")
        except ValueError:
            print("Invalid input. Please enter a valid number.")
```

### Step 3: Run the Game

```python
if __name__ == "__main__":
    main()
```

## Conclusion

This simple number guessing game demonstrates basic concepts of Python programming, including loops, conditionals, and user input handling. You can further enhance the game by adding features such as difficulty levels, score tracking, or a graphical user interface.


## Related Interview Questions

1. **What is the purpose of the `random` module in Python?**
    - The `random` module is used to generate random numbers. In this game, it is used to select a random number between 1 and 100 for the player to guess.

2. **How do you handle user input in Python?**
    - User input is handled using the `input()` function, which reads a line from input, converts it to a string, and returns it. In this game, the input is converted to an integer using `int()`.

3. **What are try-except blocks and how are they used in Python?**
    - Try-except blocks are used for exception handling in Python. They allow you to test a block of code for errors and handle them gracefully. In this game, a try-except block is used to catch `ValueError` exceptions when the user enters invalid input.

4. **Explain the use of loops in Python with an example.**
    - Loops are used to execute a block of code repeatedly. In this game, a `while` loop is used to repeatedly prompt the player for guesses until the correct number is guessed.

5. **What are conditionals and how are they used in Python?**
    - Conditionals are used to execute different blocks of code based on certain conditions. In this game, `if-elif-else` statements are used to provide feedback on whether the guessed number is too high, too low, or correct.

6. **How can you improve the performance of a Python program?**
    - Performance can be improved by optimizing algorithms, using efficient data structures, minimizing the use of global variables, and avoiding unnecessary computations. For this game, performance is not a major concern due to its simplicity.

7. **What are some ways to enhance the number guessing game?**
    - Enhancements could include adding difficulty levels, implementing score tracking, providing hints, allowing multiple players, or creating a graphical user interface.

8. **How do you test and debug a Python program?**
    - Testing can be done using unit tests, integration tests, and manual testing. Debugging can be done using print statements, logging, or using a debugger tool to step through the code and inspect variables.

These questions cover fundamental concepts that are not only relevant to the number guessing game but also to general Python programming and software development.