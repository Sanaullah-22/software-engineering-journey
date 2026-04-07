# 📘 Day 06 – Python Basics (Syntax, Variables & Data Types)

## 🖨️ Print Function
- print() is a built-in function used to display output.
- The value inside parentheses () is called an argument.

### Example:
```python
print("Hello, World")
print(30)
💬 Comments in Python
Comments are used to explain code or ignore certain lines.
Python ignores comments during execution.
Example:
Python
# This is a comment
print("Hello")
📏 Indentation
Indentation means adding spaces before code.
It defines blocks of code in Python.
Example:
Python
if (5 > 3):
    print("Hello")
📦 Variables
A variable stores data.
It is created when a value is assigned using =.
Example:
Python
age = 23
name = "Sanny"
cgpa = 3.5
🟰 Assignment Operator
= is used to assign values to variables.
⚡ Dynamic Typing
Python is dynamically typed.
No need to declare variable type explicitly.
📜 Rules for Naming Variables
Must start with a letter (a-z, A-Z) or underscore _
Can contain letters, numbers, and underscores
Case-sensitive (age and Age are different)
Cannot use keywords (like if, for, while)
Cannot start with a number
Cannot use special characters (except _)
❌ Invalid Examples:
Python
32age = 23
ag$$e = 32
✅ Valid Example:
Python
_age = 35
🔢 Data Types in Python
1. Integer (int)
Whole numbers
Example: 10, -5
2. Float (float)
Decimal numbers
Example: 3.14, -0.5
3. String (str)
Text inside quotes
Example: "Hello"
4. Boolean (bool)
True or False
📚 Collection Data Types
List
Ordered and mutable
Python
[1, 2, 3]
Tuple
Ordered and immutable
Python
(1, 2, 3)
Set
Unordered, unique elements
Python
{1, 2, 3}
Dictionary
Key-value pairs
Python
{"name": "Sanny", "age": 23}
🔍 Checking Data Type
Use type() function
Example:
Python
age = 23
print(type(age))

name = "Sanny"
print(type(name))

cgpa = 3.9
print(type(cgpa))

is_completed = True
print(type(is_completed))
⚠️ Errors I Faced
Syntax errors due to incorrect comments
Invalid variable names
Indentation mistakes
👉 Fixed them by practicing and understanding the rules.
✅ Summary
Learned Python syntax basics
Understood variables and assignment
Explored data types
Practiced writing and debugging code
