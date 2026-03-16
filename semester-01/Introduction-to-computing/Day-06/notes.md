Taking User Input in Python
Overview
In Python, we use the input() function to take input from the user during program execution.
The input() function always returns the data in string format by default.
Example 1: Taking Basic Input
Python
Copy code
a = input("Enter Your Name")
b = input("Enter Your Age")

print("Name:", a, "Age:", b)
Explanation
input() waits for the user to enter a value.
Whatever the user types is stored in the variable.
The value is stored as a string.
print() displays the output.
Example 2: Taking Numbers as Input
Python
a = input("Enter First Number")
a = int(a)

b = int(input("Enter Second Number"))

sum = a + b
print("Sum =", sum)
Explanation
Since input() returns a string, we must convert it to a numeric type before performing calculations.
Python provides type conversion functions such as:
int() → converts to integer
float() → converts to decimal number
Two Ways to Convert Input
Method 1: Convert After Input
Python

a = input("Enter a number")
a = int(a)
Method 2: Convert Directly
Python

a = int(input("Enter a number"))
Key Points
input() always returns a string.
Use type conversion when working with numbers.
int() is used for integers.
float() is used for decimal numbers.

Enter First Number: 5
Enter Second Number: 7
Sum = 12
