Day 05 – Python Basics 

1. What is Programming?

Definition

Programming is the process of communicating with a computer by writing instructions that it can understand and execute.

Explanation

Computers cannot understand human language directly. Therefore, programmers use programming languages to give instructions to computers. These instructions tell the computer what task to perform.

In simple words:

> Programming is the process of solving problems through code and turning ideas into actionable instructions for a computer.



Example tasks done through programming:

Building websites

Creating mobile applications

Automating tasks

Data analysis

Artificial intelligence systems



---

2. Syntax in Programming

Definition

Syntax refers to the set of rules that must be followed when writing code in a programming language.

Explanation

Every programming language has its own grammar rules. If these rules are not followed, the computer cannot understand the instructions.

When syntax rules are broken, the program produces an error.

Example:

print("Hello World")

If we forget the quotation marks or parentheses, Python will produce a syntax error.


---

3. What is Python?

Definition

Python is a high-level interpreted programming language used for general-purpose programming.

Explanation

Python is known for:

Simple syntax

Readable code

Large community support

Powerful libraries


It is widely used in:

Web development

Data science

Machine learning

Automation

Software development


Example:

print("Hello, World")

Here:

print() is a function

"Hello, World" is an argument



---

4. Python Syntax Basics

Example of Python syntax:

print("I am a web designer")
print(30)

Explanation

print() displays output on the screen

The value inside parentheses is called an argument



---

5. Comments in Python

Definition

A comment is a line of code that the computer ignores during execution.

Purpose of Comments

Comments are used to:

Explain code

Improve readability

Leave notes for developers


Example:

# This is a comment
print("Hello")


---

6. Indentation in Python

Python uses indentation (spaces before code) to define blocks of code.

Example:

if (5 > 3):
    print("Hello")

Explanation:

The space before print() shows that it belongs to the if block.


Without proper indentation, Python will produce an Indentation Error.


---

7. Variables in Python

Definition

A variable is used to store data that can be used later in a program.

Explanation

A variable is created when a value is assigned to it using the assignment operator (=).

Example:

age = 23
print(age)

name = "Sanny"
print(name)

Here:

age stores the value 23

name stores the value "Sanny"



---

8. Assignment Operator

The assignment operator (=) is used to assign a value to a variable.

Example:

age = 23

This means the variable age is assigned the value 23.


---

9. Dynamic Typing in Python

Python is a dynamically typed language.

Explanation

This means we do not need to specify the data type of a variable when declaring it. Python automatically detects the type.

Example:

age = 23
name = "Sanny"
cgpa = 3.5

Python automatically identifies:

age → integer

name → string

cgpa → float


Example using type():

cgpa = 3.5
print(type(cgpa), cgpa)


---

10. Rules for Defining Variables in Python

1. Variable names must start with a letter (A–Z, a–z) or underscore (_).


2. Variable names can contain letters, numbers, and underscores.


3. Variable names are case-sensitive (age and Age are different).


4. Python keywords cannot be used as variable names.



Invalid Examples

32age = 23

Invalid because variables cannot start with a number.

ag$$e = 32

Invalid because special characters are not allowed.

Valid Examples

age = 32
_age = 35

print(age)
print(_age)


---

11. Data Types in Python

Python provides several built-in data types.

1. Integer (int)

Whole numbers.

Examples:

10
20
-5


---

2. Float (float)

Numbers with decimal points.

Examples:

3.14
-0.234


---

3. String (str)

Text data enclosed in quotes.

Examples:

"Hello"
'Python'


---

4. Boolean (bool)

Represents True or False values.

Example:

True
False


---

5. List

An ordered and mutable collection of elements.

Example:

[1, 2, 3]


---

6. Tuple

An ordered but immutable collection.

Example:

(1, 2, 3)


---

7. Set

An unordered collection of unique elements.

Example:

{1, 2, 3}


---

8. Dictionary

Stores key-value pairs.

Example:

{"name": "Alice", "age": 23}


---

12. Examples of Data Types

age = 23
print(type(age))

name = "Sanny"
print(type(name), name)

cgpa = 3.9
print(type(cgpa), cgpa)

is_completed = True
print(type(is_completed), is_completed)


---

13. Type Casting in Python

Definition

Type casting means converting one data type into another.

Example

a = 32
print(type(a), a)

# Converting integer to string
b = str(a)
print(type(b), b)

c = 2
d = float(c)
print(type(d), d)

Explanation

str() converts data into string

float() converts data into decimal number

int() converts data into integer



---

Summary of Day 05

Today I learned the fundamentals of Python programming, including:

What programming means

Syntax and errors

Python basics

Comments and indentation

Variables and assignment operators

Rules for variable naming

Built-in data types

Type casting


These concepts form the foundation of programming in Python and are essential before learning advanced topics like loops, functions, and data structure.
