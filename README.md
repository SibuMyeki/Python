 # Introduction to Python
Python is a widely used general-purpose, high level programming language. 
Python is a programming language that lets you work quickly and integrate systems more efficiently. 
its syntax allows programmers to express their concepts in fewer lines of code. 

## Comments 

Comments in Python are used to provide explanations or annotations within your code. 
They are not executed by the Python interpreter and are meant to be human-readable.

##Single-Line Comments: Single-line comments are used for short comments and are preceded by the # symbol.
Everything on the same line after # is considered a comment and is ignored by the Python interpreter. 

This is a single-line comment 
```
 print("Hello, World")  This comment is at the end of a line of code
 
```
 
## Multi-Line Comments or Docstrings: 
Multi-line comments are typically used for longer explanations and documentation.
In Python, these are often represented as docstrings (used for documentation of functions, classes, and modules).
A docstring is enclosed in triple quotes (''' or """) and can span multiple lines

```
This is a multi-line comment or a docstring.
It can span multiple lines and is often used for documenting functions, classes, or modules.

def my_function():
    """
    This is also a docstring.
    It provides documentation for the function.
     """
    pass
```
# Introduction to Variables

Variables are simple containers for storing data values and Python has no commands for declaring a variable. 

1. ## Variable Naming Rules: 

Variable names are case-sensitive, meaning "myVariable" and "myvariable" are treated as different variables. 

Variable names must start with a letter (a-z, A-Z) or an underscore (_) character. 

Subsequent characters in variable names can include letters, digits (0-9), and underscores. 

Variable names cannot contain spaces or special characters like @, $, %, etc. 

2. ## Variable Assignment: 

Assigning a value to a variable is known as variable assignment. In Python, you use the = operator for assignment. 

For example, to assign the integer value 10 to a variable called "x," you would write: x = 10. 

3. ## Data Types: 

Variables have associated data types that define the kind of data they can hold. Common data types include: 

Integers (int): Whole numbers, e.g., 5, -3, 1000. 

Floating-point numbers (float): Decimal numbers, e.g., 3.14, -0.5, 2.0. 

Strings (str): Text, e.g., "Hello, World!". 

Booleans (bool): True or False. 

 

4. ## Variable Usage: 

Once a value is assigned to a variable, you can use that variable in expressions, calculations, or simply to display the value. 

For example, you can perform operations like addition, subtraction, and concatenation on variables. 

5. ## Variable Scope: 

Variables have a scope, which defines where in the code they are accessible.
Variables can be local (only accessible in a specific function or block) or global (accessible throughout the entire program). 

6. ## Reassignment: 

You can change the value of a variable by assigning it a new value. This is called reassignment. 

For example, you can do x = 20 to change the value of "x" to 20. 

Example of a code :
```
# Variable assignment
x = 10
y = "Hello, World"

# Variable usage
result = x + 5
greeting = y + " Welcome!"

# Variable reassignment
x = 20

# Displaying values
print("Result:", result)
print("Greeting:", greeting)
print("Updated x:", x)
```


# Introduction to Data Types

Data types in computer programming refer to the classification or categorization of data based on its type or value. 
Different data types are used to represent various kinds of information, such as numbers, text, and more, in a format that the computer can understand and manipulate. 

 ## Common data type

 Integer (int): This data type is used to represent whole numbers, both positive and negative, without any decimal points. Examples include -1, 0, 42.

Floating-Point (float): Floating-point data types are used to represent numbers with decimal points or fractional parts. Examples include -3.14, 2.71828.

String (str): Strings are used to represent sequences of characters, such as text. "Hello, World!" is an example of a string.

Boolean (bool): Boolean data types have only two possible values: True and False. They are often used for logical operations and conditional statements.

List: Lists are used to store ordered collections of items. Elements in a list can have different data types.
For example, [1,2,3] is a list of integers.

Tuple: Tuples are similar to lists but are immutable, meaning their elements cannot be changed once they are defined.
They are often used to group related values. An example is (1, 'apple', 3.14).

Dictionary (dict): Dictionaries store key-value pairs. Each key is associated with a value, allowing for efficient lookup and storage of data.
For example, {'name': 'John', 'age': 30} is a dictionary.

Set: Sets are used to store collections of unique values. They do not allow duplicate elements. An example is {1, 2, 3}.

None: This data type represents the absence of a value or a null value. It is often used to indicate missing or uninitialized data.

Custom Data Types (Objects, Classes): In many programming languages, you can define your own custom data types using objects or classes. 
These allow you to encapsulate data and functionality into user-defined structures.


# Operators 
 Operators are symbols or special keywords used to perform operations on variables and values. 
 Python provides a variety of operators, which can be categorized into the following groups:


 ## Arithmetic Operators:

+ + (Addition): Adds two numbers.
  

-  (Subtraction) -: Subtracts the right operand from the left operand.
  
- (Multiplication) * : Multiplies two numbers.
 
- (Division): / Divides the left operand by the right operand, yielding a floating-point result.

// (Floor Division): Divides the left operand by the right operand and truncates the decimal part to the nearest integer.

% (Modulus): Returns the remainder of the division.

** (Exponentiation): Raises the left operand to the power of the right operand.
  
## Comparison Operators:

== (Equal): Checks if two values are equal.

!= (Not Equal): Checks if two values are not equal.

< (Less Than): Checks if the left operand is less than the right operand.

> (Greater Than): Checks if the left operand is greater than the right operand.
> 
<= (Less Than or Equal To): Checks if the left operand is less than or equal to the right operand.

>= (Greater Than or Equal To): Checks if the left operand is greater than or equal to the right operand.

## Logical Operators:

and (Logical AND): Returns True if both operands are True.

or (Logical OR): Returns True if at least one of the operands is True.

not (Logical NOT): Inverts the logical value of the operand.

## Assignment Operators:

= (Assignment): Assigns a value to a variable.

+= (Addition Assignment): Adds the right operand to the left operand and assigns the result to the left operand.

-= (Subtraction Assignment): Subtracts the right operand from the left operand and assigns the result to the left operand.

*= (Multiplication Assignment): Multiplies the left operand by the right operand and assigns the result to the left operand.

/= (Division Assignment): Divides the left operand by the right operand and assigns the result to the left operand.

//= (Floor Division Assignment): Performs floor division and assigns the result to the left operand.

%= (Modulus Assignment): Calculates the modulus and assigns the result to the left operand.

**= (Exponentiation Assignment): Raises the left operand to the power of the right operand and assigns the result to the left operand.

## Membership Operators:

in: Returns True if a value is found in a sequence (e.g., a list, tuple, or string).

not in: Returns True if a value is not found in a sequence.

## Identity Operators:

is: Returns True if two variables reference the same object.

is not: Returns True if two variables reference different objects.

Bitwise Operators (for working with binary representations):

& (Bitwise AND)

| (Bitwise OR)

^ (Bitwise XOR)

~ (Bitwise NOT)

<< (Left Shift)

>> (Right Shift)
