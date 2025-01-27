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