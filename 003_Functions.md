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
      
+ The above statement creates a module object named math. If you print the module object, you get some information about it like below.

      >>> print math
      <module 'math' (built-in)>
      
The module object contains the functions and variables defined in the module. To access one of the functions, you have to specify the name of the module and the name of the function, separated by a dot, This format is called dot notation

#### Example:

     >>> pi_value = math.pi
     >>> pi_value
     3.141592653589793

# 17. Adding new functions

**Ans:** Apart from the build-in functions, We can also build our own functions based on our requirement.

+ Here is an example of user defined function:

      def print_lyrics():
          print "I'm a lumberjack, and I'm okay."
          print "I sleep all night and I work all day."
          
          
#### Explanation:

**Ans:** **def** is a keyword that indicates that this is a function definition. The name of the function is **print_lyrics**. The rules for function names are the same as for variable names: letters, numbers and some punctuation marks are legal, but the first character can’t be a number. You can’t use a keyword as the name of a function, and you should avoid having a variable
and a function with the same name. The empty parentheses after the name indicate that this function doesn’t take any arguments.

The first line of the function definition is called the header; the rest is called the body. The header has to end with a colon and the body has to be indented. By convention, the indentation is always four spaces. The body can contain any number of statements.

#### The syntax for calling the new function is the same as for built-in functions:

    >>> print_lyrics()
    I'm a lumberjack, and I'm okay.
    I sleep all night and I work all day.

### 18. Variables and parameters are local

**Ans:** When you create a variable inside a function, it is local, which means that it only exists inside the function.






    





    
    
    
    
    
    
    
    
    
    
    
    
    
    
    


