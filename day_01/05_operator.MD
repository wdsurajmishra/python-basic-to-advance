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