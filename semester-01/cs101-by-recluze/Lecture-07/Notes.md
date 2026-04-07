📘 Day 07 – Python Basics

## 🔹 Typecasting (Data Type Conversion)

Typecasting means converting one data type into another.

### Example:
```python
a = 32
print(type(a), a)

# converting int to string
b = str(a)
print(type(b), b)

c = 2
d = float(c)
print(type(d), d)
🔹 Taking User Input
By default, Python takes input as a string.
Example:
Python
a = input("Enter Your Name: ")
b = input("Enter Your Age: ")

print("Name:", a, "Age:", b)
Converting Input into Numbers:
Python
a = input("Enter First Number: ")
a = int(a)

b = int(input("Enter Second Number: "))

sum = a + b
print("Sum =", sum)
📝 Important:
Input always returns a string
Convert using:
int()
float()
🔹 Comments in Python
Comments are used to explain code and are ignored by the Python interpreter.
Types of Comments:
1. Single-line Comment
Python
# This is a single-line comment
print("Hello")
2. Multi-line Comment
Python
"""
This is a multi-line comment
Used for longer explanations
"""
🔹 Escape Sequences
Escape sequences are used to include special characters in strings.
Common Escape Sequences:
Sequence
Meaning
\n
New Line
\t
Tab Space
\\
Backslash
\"
Double Quote
\'
Single Quote
Example:
Python
print("Hello \n World")
print("Hello \t World")
print("Backslash: \\")
print("Double Quote: \" ")
print("Single Quote: \' ")
🔹 Print Statement
The print() function is used to display output.
Basic Example:
Python
print("Hello World", "Sanny", 5)
Customizing Output:
Using sep:
Python
print("Hello", "World", sep=",")
Using end:
Python
print("Hello", end=", ")
print("World")
🚀 Summary
Learned typecasting (int, str, float)
Understood user input and conversions
Practiced comments for better readability
Used escape sequences for formatting
Customized output using print()
