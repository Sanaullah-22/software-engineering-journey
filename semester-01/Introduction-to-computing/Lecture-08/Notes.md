
# 📘 Day 08 – Python Practice

## 🔹 Topics Covered
- Conditional Statements (if, elif, else)
- Nested Conditions
- Modulus Operator (%)
- String Methods (.lower())
- Match-Case Statement (Alternative to if-elif)

---

## 🧮 1. Age Calculator

### 💡 Concept:
Checks whether a person is Adult, Teenager, or Child based on age.

python
Age = int(input("Enter your Age"))

if Age >= 18:
    print("You Are Adult")
elif Age >= 13:
    print("You Are Teenager")
else:
    print("You are a Child")


### ✅ Output:

You Are Adult


---

## 🚦 2. Traffic Light System

### 💡 Concept:
Uses user input and .lower() to handle case sensitivity.

python
color = input("Enter a color").lower()

if color == "red":
    print("STOP 🚫")
elif color == "green":
    print("GO 🏃‍♂️‍➡️")
elif color == "yellow":
    print("LOOK 👀")
else:
    print("Wrong Color 😡")


### ✅ Output:

LOOK 👀


---

## 🔢 3. Odd Even Checker

### 💡 Concept:
Uses modulus operator % to check even or odd numbers.

python
number = int(input("Enter a Number"))

if number % 2 == 0:
    print("Even")
else:
    print("Odd")


### ✅ Output:

Odd


---

## 🔐 4. Nested Conditions (Login System)

### 💡 Concept:
Demonstrates nesting inside conditions.

python
username = input("Enter username ").lower()
password = int(input("Enter Password"))

if (username == "admin" and password == 123):
    print("Login Successfully")
else:
    if (username != "admin"):
        print("Wrong Username")
    else:
        print("wrong Pass")


### ✅ Output:

Login Successfully


---

## 🔄 5. Match-Case Statement

### 💡 Concept:
match-case is an alternative to if-elif-else (introduced in Python 3.10).

python
color = input("enter a color").lower()

match color:
    case "green":
        print("GO")
    case "yellow":
        print("LOOK")
    case "red":
        print("STOP")
    case _:
        print("Wrong Color")


---

## 📌 Key Learnings
- Conditional logic helps in decision making
- % operator is useful for number checks
- .lower() improves input handling
- Nesting allows complex conditions
- match-case makes code cleaner and readable

---

## 🚀 Progress
Day 08 Completed ✅  
Learning Python step by step 💻🔥
