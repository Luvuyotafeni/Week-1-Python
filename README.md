# Week-1-Python
Python in the job market
Integrating applications with MySQL is in high demand because MySQL and Python are both open-source applications. This means that some companies are switching over from their current expensive systems to open-source systems. YouTube and BitTorrent are examples of companies that use Python.

Network programming in Python is another option, which requires an extensive knowledge of how networking is controlled. Another fields for a Python programmer are Software Engineer, Software developer, Research Analyst, Data Analyst and Data Scientist; you will often be required to have database experience when working in this field.

History of Python
Python was conceived in the late 1980s and Guido van Rossum started implementing it at CWI in the Netherlands in December 1989. It is a relatively simple language that includes a standard library that provides modules for a large number of processes that programs deal with. This approach keeps Python simple yet reliable programming language.

Python has an easy-to-use syntax that is focused on the programmer who must type in the program, read what was typed, and provide formal documentation for the program. Many languages have syntax focused on developing a simple, fast compiler; but those languages may sacrifice readability and can be more difficult to write. Python strikes a good balance between fast compilations and readability, and it is easier to write applications.

Comments in Python
comments in programming language are what we use for programmer benefits such as knowing or highlighting what the code is about, in python we use the # to write comments, these are ignored by the compiler or interpreter, which means it does not affect the source code.

Escape patterns
Backslash character (\)	 \\
New line feed	\n 
Tab	\t 
Vertical tab	\v 
Backspace	\b
Carriage return	\r
Single quote (useful in strings enclosed in single quotes: ‘hello \ ‘World’)	\' 
Double quote (useful in strings enclosed in single quotes: “hello \ “World”)	\"

Reserved words
and
as
assert 
break 
class
continue
def
del
elif
else
except 
false
finally 
from 
for 
global
if 
import 
is 
in 
lambda 
none 
nonlocal 
not
or
pass 
raise 
return 
true 
try 
while 
with 
yield

Installing Anaconda on Windows
Visit Anaconda.com/downloads
Select Windows
Download the .exe installer
Open and run the .exe installer
Open the Anaconda Prompt and run some Python code

Introduction to Variables
Variables are containers in a computer’s memory, to hold a different number of data items or values. Variable Naming Rules:
Variable names must start with a letter (a-z, A-Z) or an underscore (_).
The rest of the variable name can consist of letters, numbers, and underscores.
Variable names are case-sensitive (e.g., myVar and myvar are different variables).
Python reserved words (keywords) cannot be used as variable names.

Using variables
each variable is assigned a data type, the data type is illustrated by what valur you assign the variable name to.eg num=10 or name = "luvuyo".
Values of the same type can be manipulated together.

Casting in python
this involves the process of converting a variable from one data type to another without the loss of data in the variable being converted.
casting ways
Implicitly: The compiler automatically casts a value from one data type to another when assured that there will be no data loss.
Explicitly: A value cannot be automatically cast from one data type to another if it will result in data loss. Extra code has to be written to ensure that the value stays the same and only the data type changes.

Data Types
Integers
Booleans
Floating point numbers
Complex numbers
Strings
Literals are values that never change, they are not assigned to a variable, and therefore are literal values
Integers	 These represent numbers in an unlimited range. This is only limited by a machine’s memory.
 Booleans	 Evaluate to ‘True or False’, 1 or 0 respectively.
 Floating point numbers	 Floating-point numbers represent double-precision numbers.
 Complex numbers	 Complex numbers represent numbers as a pair of double-precision numbers.
 Strings	 A sequence of Unicode characters e.g. a word or a sentence that can be manipulated.

 Integers
 In Python, integers are a data type used to represent whole numbers. They can be positive or negative, and they do not have decimal or fractional parts. In Python, you can perform various operations with integers, such as addition, subtraction, multiplication, division, and more.
in python you can add integers in a print statement but cant add integers with string without converting them first. a comma in python print statement means a space or another character will displayed into the print statement.

Booleans
Boolean data type has corresponding integer values. There are only two possible values that a Boolean variable can have, True (1) or False (0). When returning Booleans as strings they are seen as “True” and “False”, and never as “1” and “0”. True and False are case-sensitive in Python. Boolean tests whether conditions are valid or not. The three logical operators used to test conditions between two arguments are:
The and-operator
The or operator
The not operator
The next section will refresh your memory, and you will soon be able to write programs that execute operations automatically based on decisions (such as the if statement explained in week 2). The following variable values are considered False:
False
None
Zero for any numeric data type, 0, 0.0, 0j
An empty sequence or mapping. Like a list or tuple, ' ', ( ), [ ], { } 
Instances of user-defined classes, where a class that defines a __bool__() method returns zero or False.
All values returned otherwise are always considered true. This means that many objects will always return true.
Operators and built-in functions that have a Boolean result always return (False or 0) or (True or 1). The Boolean or and and operations always return only one of the options, either True or False.
Manipulate Booleans
Syntax	 Description
a or b	 
If either a or b is True, then the result will be True. 
If both a and b are False then the result will be False.
a and b	 If a and b are True, then the result will be True. Otherwise, the result will be False.
not a	 If a is True, False is returned. If a is False, True is returned.

Floating point numbers
In Python, floating-point numbers are used to represent real numbers and are used when more precision is needed than provided by integers. Floating-point numbers can represent a wide range of values, including fractional numbers. Python uses the float data type to represent floating-point numbers.
to convert the number after the decimal, you specify the number of decimal places you want then you put f as a suffix

Complex numbers
Complex numbers are two numbers contained in a single variable. The first part of a complex number is the real part (float), and the second part is the imaginary part (float), assigned in this manner: complex(real, image). Imaginary numbers are real multiples of the imaginary unit, written with a suffix of j (J). The imaginary part is the square root of -1. Python has built-in support for complex numbers. The latter notation is written as follows: 4+8j.

Strings
when declaring or assigning a string you can write the values inside the quotation marks or you can write them inside and str() bracket.
In Python, strings are sequences of characters, represented either within single quotes (') or double quotes ("). Strings are used to store textual data and can contain letters, numbers, symbols, and spaces. Python provides a variety of operations and functions to manipulate and work with strings.
single_quoted_string = 'Hello, World!'
double_quoted_string = "Hello, World!"
multiline_string = '''This is a
multi-line
string.'''
repeated_string = "Python " * 3  .
Using the ‘+=‘ operator with strings
The ‘+=‘ operator adds values to an existing variable
The ‘+=‘ operator’s functionality is not only limited to strings, it can be used with other data types, too.

Lambda Expressions
Lambda expressions, also known as lambda functions, are small, anonymous (unnamed) functions in Python. They can have any number of input parameters, but can only have one expression. Lambda functions are often used when you need a simple function for a short period of time and don't want to formally define a full function using the def keyword.

Conventions about the content and formatting of documentation strings
In Python, documentation strings (often referred to as docstrings) are used to document modules, classes, functions, and methods. Properly formatted docstrings are important as they provide a way for developers to understand how to use the code, what parameters are expected, what the function or method does, and what it returns. Following conventions ensures consistency across Python projects, making the code more readable and maintainable.

Operators
1. Arithmetic Operators:
These operators are used to perform mathematical operations.
+ Addition: Adds two operands.
- Subtraction: Subtracts right operand from the left operand.
* Multiplication: Multiplies two operands.
/ Division: Divides left operand by right operand.
% Modulus: Returns the remainder of the division.
** Exponent: Raises left operand to the power of the right operand.
// Floor Division: Returns the quotient of the division, rounded down to the nearest whole number.

2. Comparison Operators:
These operators are used to compare values.
== Equal to: True if the operands are equal.
!= Not equal to: True if the operands are not equal.
< Less than: True if the left operand is less than the right operand.
> Greater than: True if the left operand is greater than the right operand.
<= Less than or equal to: True if the left operand is less than or equal to the right operand.
>= Greater than or equal to: True if the left operand is greater than or equal to the right operand.
> 
3. Logical Operators:
These operators are used to combine conditional statements.
and Logical AND: True if both operands are true.
or Logical OR: True if at least one operand is true.
not Logical NOT: True if the operand is false (complements the operand).

4. Assignment Operators:
These operators are used to assign values to variables.
= Assignment: Assigns the value of the right operand to the left operand.
+= Addition Assignment: Adds the right operand to the left operand and assigns the result to the left operand.
-= Subtraction Assignment: Subtracts the right operand from the left operand and assigns the result to the left operand.
*= Multiplication Assignment: Multiplies the left operand by the right operand and assigns the result to the left operand.
/= Division Assignment: Divides the left operand by the right operand and assigns the result to the left operand.
%= Modulus Assignment: Performs modulus on the left operand with the right operand and assigns the result to the left operand.
**= Exponent Assignment: Raises the left operand to the power of the right operand and assigns the result to the left operand.
//= Floor Division Assignment: Performs floor division on the left operand with the right operand and assigns the result to the left operand.

5. Membership Operators:
These operators are used to test if a value is a member of a sequence (such as a list, tuple, or string).
in True if the value is found in the sequence.
not in True if the value is not found in the sequence.

6. Identity Operators:
These operators are used to compare the memory locations of two objects.
is True if the operands are identical (refer to the same object).
is not True if the operands are not identical (do not refer to the same object).
These are some of the basic operators in Python. Understanding these operators is essential for writing Python programs and performing various operations on variables and data.

Using Operators
1. Arithmetic Operators:
Arithmetic operators are used to perform mathematical operations.
a = 10
b = 5
# Addition
sum = a + b
print("Sum:", sum)
# Subtraction
difference = a - b
print("Difference:", difference)
# Multiplication
product = a * b
print("Product:", product)
# Division
quotient = a / b
print("Quotient:", quotient)
# Modulus (remainder)
remainder = a % b
print("Remainder:", remainder)
# Exponent
exponential = a ** b
print("Exponential:", exponential)
2. Comparison Operators:
Comparison operators are used to compare values.
x = 10
y = 20
# Equal to
print(x == y)  # False
# Not equal to
print(x != y)  # True
# Greater than
print(x > y)   # False
# Less than
print(x < y)   # True
# Greater than or equal to
print(x >= y)  # False
# Less than or equal to
print(x <= y)  # True
3. Logical Operators:
Logical operators are used to combine conditional statements.
p = True
q = False
# Logical AND
print(p and q)  # False
# Logical OR
print(p or q)   # True
# Logical NOT
print(not p)    # False
4. Assignment Operators:
Assignment operators are used to assign values to variables.
python
x = 10
# Addition assignment
x += 5  # Equivalent to x = x + 5
# Subtraction assignment
x -= 3  # Equivalent to x = x - 3
# Multiplication assignment
x *= 2  # Equivalent to x = x * 2
# Division assignment
x /= 4  # Equivalent to x = x / 4
print("Updated x:", x)  # Output: 3.0

