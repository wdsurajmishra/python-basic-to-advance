# Python 2 vs Python 3: Major Differences

## Print Statement
- **Python 2**: `print` is treated as a statement.
    ```python
    print "Hello, World!"
    ```
- **Python 3**: `print` is treated as a function.
    ```python
    print("Hello, World!")
    ```

## Integer Division
- **Python 2**: Division of two integers produces an integer.
    ```python
    print 3 / 2  # Output: 1
    ```
- **Python 3**: Division of two integers produces a float.
    ```python
    print(3 / 2)  # Output: 1.5
    ```

## Unicode
- **Python 2**: `str` type stores bytes, `unicode` type stores Unicode characters.
    ```python
    s = u"Hello, World!"
    ```
- **Python 3**: `str` type stores Unicode characters, `bytes` type stores bytes.
    ```python
    s = "Hello, World!"
    ```

## xrange
- **Python 2**: `xrange` is used for creating an iterator.
    ```python
    for i in xrange(5):
        print i
    ```
- **Python 3**: `range` is used for creating an iterator.
    ```python
    for i in range(5):
        print(i)
    ```

## Exception Handling
- **Python 2**: Exceptions are handled using `as` keyword.
    ```python
    try:
        raise Exception("An error occurred")
    except Exception, e:
        print e
    ```
- **Python 3**: Exceptions are handled using `as` keyword.
    ```python
    try:
        raise Exception("An error occurred")
    except Exception as e:
        print(e)
    ```

    ## Interview Question

    ### What are the key differences between Python 2 and Python 3?

    When preparing for an interview, it's important to understand the major differences between Python 2 and Python 3. Here are some key points to consider:

    1. **Print Statement vs Print Function**:
        - Python 2: `print` is a statement.
        - Python 3: `print` is a function.

    2. **Integer Division**:
        - Python 2: Division of two integers results in an integer.
        - Python 3: Division of two integers results in a float.

    3. **Unicode Handling**:
        - Python 2: `str` type is for bytes, `unicode` type is for Unicode characters.
        - Python 3: `str` type is for Unicode characters, `bytes` type is for bytes.

    4. **Iterators**:
        - Python 2: Uses `xrange` for creating iterators.
        - Python 3: Uses `range` for creating iterators.

    5. **Exception Handling**:
        - Python 2: Uses a comma to separate the exception type and variable.
        - Python 3: Uses the `as` keyword to separate the exception type and variable.

    Understanding these differences can help you write more compatible and efficient code, and demonstrate your knowledge during an interview.
