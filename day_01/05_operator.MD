1. Arithmetic Operator - These are used for basic mathematical operations.
    +   : Addition
        ```python
        a = 5
        b = 3
        print(a + b)  # Output: 8
        ```
    -   : Subtraction
        ```python
        a = 5
        b = 3
        print(a - b)  # Output: 2
        ```
    *   : Multiplication
        ```python
        a = 5
        b = 3
        print(a * b)  # Output: 15
        ```
    /   : Division
        ```python
        a = 5
        b = 3
        print(a / b)  # Output: 1.6666666666666667
        ```
    %   : Modulus
        ```python
        a = 5
        b = 3
        print(a % b)  # Output: 2
        ```
    //  : Floor Division
        ```python
        a = 5
        b = 3
        print(a // b)  # Output: 1
        ```
    **  : Exponentiation
        ```python
        a = 5
        b = 3
        print(a ** b)  # Output: 125
        ```

2. Comparison Operator - These are used to compare values.
    ==  : Equal
        ```python
        a = 5
        b = 3
        print(a == b)  # Output: False
        ```
    !=  : Not Equal 
        ```python
        a = 5
        b = 3
        print(a != b)  # Output: True
        ```
    >   : Greater than
        ```python
        a = 5
        b = 3
        print(a > b)  # Output: True
        ```
    <   : Less Than
        ```python
        a = 5
        b = 3
        print(a < b)  # Output: False
        ```
    >=  : Greater than or Equal to
        ```python
        a = 5
        b = 3
        print(a >= b)  # Output: True
        ```
    <=  : Less than or Equal to
        ```python
        a = 5
        b = 3
        print(a <= b)  # Output: False
        ```

3. Assignment Operator - These are used to assign values to variables.
    =   : Assign value
        ```python
        a = 5
        print(a)  # Output: 5
        ```
    +=  : Add and Assign
        ```python
        a = 5
        a += 3
        print(a)  # Output: 8
        ```
    -=  : Subtract and Assign
        ```python
        a = 5
        a -= 3
        print(a)  # Output: 2
        ```
    *=  : Multiply and Assign
        ```python
        a = 5
        a *= 3
        print(a)  # Output: 15
        ```
    /=  : Divide and Assign
        ```python
        a = 5
        a /= 3
        print(a)  # Output: 1.6666666666666667
        ```
    %=  : Modulus and Assign
        ```python
        a = 5
        a %= 3
        print(a)  # Output: 2
        ```
    //=  : Floor divide and Assign
        ```python
        a = 5
        a //= 3
        print(a)  # Output: 1
        ```
    **=  : Exponentiate and Assign
        ```python
        a = 5
        a **= 3
        print(a)  # Output: 125
        ```

4. Logical Operator - These are used to combine conditional statements.
    and : Returns True if both statements are true
        ```python
        a = True
        b = False
        print(a and b)  # Output: False
        ```
    or  : Returns True if one of the statements is true
        ```python
        a = True
        b = False
        print(a or b)  # Output: True
        ```
    not : Reverse the result, returns False if the result is true
        ```python
        a = True
        print(not a)  # Output: False
        ```

5. Identity Operator - These are used to compare objects, not if they are equal, but if they are actually the same object, with the same memory location.
    is  : Returns True if both variables are the same object
        ```python
        a = [1, 2, 3]
        b = a
        print(a is b)  # Output: True
        ```
    is not : Returns True if both variables are not the same object
        ```python
        a = [1, 2, 3]
        b = [1, 2, 3]
        print(a is not b)  # Output: True
        ```

6. Membership Operator - These are used to test if a sequence is presented in an object.
    in  : Returns True if a sequence with the specified value is present in the object
        ```python
        a = [1, 2, 3]
        print(2 in a)  # Output: True
        ```
    not in : Returns True if a sequence with the specified value is not present in the object
        ```python
        a = [1, 2, 3]
        print(4 not in a)  # Output: True
        ```

7. Bitwise Operator - These are used to compare (binary) numbers.
    &   : AND
        ```python
        a = 5  # 0101
        b = 3  # 0011
        print(a & b)  # Output: 1 (0001)
        ```
    |   : OR
        ```python
        a = 5  # 0101
        b = 3  # 0011
        print(a | b)  # Output: 7 (0111)
        ```
    ^   : XOR
        ```python
        a = 5  # 0101
        b = 3  # 0011
        print(a ^ b)  # Output: 6 (0110)
        ```
    ~   : NOT
        ```python
        a = 5  # 0101
        print(~a)  # Output: -6 (inverts all bits)
        ```
    <<  : Zero fill left shift
        ```python
        a = 5  # 0101
        print(a << 1)  # Output: 10 (1010)
        ```
    >>  : Signed right shift
        ```python
        a = 5  # 0101
        print(a >> 1)  # Output: 2 (0010)
        ```

        8. Augmented Assignment Operator - These are used to perform an operation and assign the result to the same variable in a single statement.
            +=  : Add and Assign
                ```python
                a = 5
                a += 3
                print(a)  # Output: 8
                ```
            -=  : Subtract and Assign
                ```python
                a = 5
                a -= 3
                print(a)  # Output: 2
                ```
            *=  : Multiply and Assign
                ```python
                a = 5
                a *= 3
                print(a)  # Output: 15
                ```
            /=  : Divide and Assign
                ```python
                a = 5
                a /= 3
                print(a)  # Output: 1.6666666666666667
                ```
            %=  : Modulus and Assign
                ```python
                a = 5
                a %= 3
                print(a)  # Output: 2
                ```
            //=  : Floor divide and Assign
                ```python
                a = 5
                a //= 3
                print(a)  # Output: 1
                ```
            **=  : Exponentiate and Assign
                ```python
                a = 5
                a **= 3
                print(a)  # Output: 125
                ```
            &=  : Bitwise AND and Assign
                ```python
                a = 5  # 0101
                a &= 3  # 0011
                print(a)  # Output: 1 (0001)
                ```
            |=  : Bitwise OR and Assign
                ```python
                a = 5  # 0101
                a |= 3  # 0011
                print(a)  # Output: 7 (0111)
                ```
            ^=  : Bitwise XOR and Assign
                ```python
                a = 5  # 0101
                a ^= 3  # 0011
                print(a)  # Output: 6 (0110)
                ```
            <<= : Left shift and Assign
                ```python
                a = 5  # 0101
                a <<= 1
                print(a)  # Output: 10 (1010)
                ```
            >>= : Right shift and Assign
                ```python
                a = 5  # 0101
                a >>= 1
                print(a)  # Output: 2 (0010)
                ```
    ## Interview Questions

    1. **What is the difference between `==` and `is` operators in Python?**
        - `==` checks if the values of two operands are equal.
        - `is` checks if two operands refer to the same object in memory.

    2. **How does the `//` operator differ from the `/` operator in Python?**
        - `//` performs floor division, which returns the largest integer less than or equal to the division result.
        - `/` performs true division, which returns a floating-point result.

    3. **Explain the use of the `not` operator in Python.**
        - The `not` operator is used to invert the boolean value of its operand. If the operand is `True`, it returns `False`, and vice versa.

    4. **What is the purpose of the `+=` operator in Python?**
        - The `+=` operator adds the right operand to the left operand and assigns the result to the left operand.

    5. **How do the `&` and `|` bitwise operators work in Python?**
        - `&` performs a bitwise AND operation, where each bit of the output is `1` if the corresponding bits of both operands are `1`.
        - `|` performs a bitwise OR operation, where each bit of the output is `1` if at least one of the corresponding bits of the operands is `1`.

    6. **What is the difference between `a << 1` and `a >> 1` in Python?**
        - `a << 1` shifts the bits of `a` to the left by one position, effectively multiplying `a` by 2.
        - `a >> 1` shifts the bits of `a` to the right by one position, effectively dividing `a` by 2 and discarding any remainder.

    7. **Can you explain the use of the `in` and `not in` operators with an example?**
        - The `in` operator checks if a value exists within a sequence (e.g., list, string).
            ```python
            a = [1, 2, 3]
            print(2 in a)  # Output: True
            ```
        - The `not in` operator checks if a value does not exist within a sequence.
            ```python
            a = [1, 2, 3]
            print(4 not in a)  # Output: True
            ```

    8. **What is the result of `5 ** 3` in Python and why?**
        - The result of `5 ** 3` is `125` because the `**` operator performs exponentiation, raising `5` to the power of `3`.

    9. **How does the `~` bitwise operator work in Python?**
        - The `~` operator inverts all the bits of its operand, effectively computing the bitwise NOT. For example, `~5` results in `-6`.

    10. **What is the difference between `a += b` and `a = a + b`?**
        - Both `a += b` and `a = a + b` perform the same operation of adding `b` to `a` and assigning the result to `a`. However, `a += b` is an in-place operation and may be more efficient for mutable objects.