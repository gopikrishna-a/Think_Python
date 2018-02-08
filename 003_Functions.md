# Chapter: 3 Functions

### 14. What is a Function?

**Ans:** Function is a named sequence of statements that performs a computation. When you define a function, you specify the name and the sequence of statements. Later, you can “call” the function by name.

#### Example:

    >>> type(32)
    <type 'int'>
    
+ In the above example  the name of the function is type. The expression in parentheses is called the argument of the function. The result, for this function, is the type of the argument.

+ It is common to say that a function “takes” an argument and “returns” a result. The result is called the return value.

### 15. Type conversion functions

**Ans:** Python provides built-in functions that convert values from one type to another. 

#### 15.1 int()

**Ans:** The int function takes any value and converts it to an integer, if it can, or complains otherwise

    >>> int('32')
    32
    >>> int('Hello')
    ValueError: invalid literal for int(): Hello

**Note:** int() can convert floating-point values to integers, but it doesn’t round off; it chops off the fraction part:

    >>> int(3.99999)
    3
    >>> int(-2.3)
    -2
    
#### 15.2 float()

**Ans:** float() converts integers and strings to floating-point numbers

    >>> float(32)
    32.0
    >>> float('3.14159')
    3.14159
    
#### 15.3 str()

**Ans:** str() converts its argument to a string

    >>> str(32)
    '32'
    >>> str(3.14159)
    '3.14159'
    
### 16. Math functions

**Ans:** Python has a math module that provides most of the familiar mathematical functions. A module is a file that contains a collection of related functions.

+ Before we can use the module, we have to import it

      >>> import math
      



    





    
    
    
    
    
    
    
    
    
    
    
    
    
    
    


