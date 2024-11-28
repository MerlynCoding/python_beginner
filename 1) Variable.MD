# Python Basics: Notes and Examples

This document summarizes fundamental Python concepts demonstrated through simple code examples. The focus is on printing, variables, and basic data types.

## 1. **Introduction to Python**
- Python is a versatile programming language ideal for beginners.
- Use the `print()` function to display output.

### Example:
```python
# This is my first Python program
print("I like pizza!")
print("It's really good!")
```

**Output:**
```
I like pizza!
It's really good!
```

---

## 2. **Variables**
- Variables store values (e.g., strings, integers, floats, booleans).
- They can represent names, favorite items, or contact information.

### Example:
```python
first_name = "Bro"
food = "pizza"
email = "Bro123@fake.com"

print(f"Hello {first_name}")
print(f"You like {food}")
print(f"Your email is: {email}")
```

**Output:**
```
Hello Bro
You like pizza
Your email is: Bro123@fake.com
```

---

## 3. **Data Types**

### **Strings**
Strings are sequences of characters, enclosed in quotes.

```python
first_name = "Bro"
food = "pizza"
email = "Bro123@fake.com"
```

### **Integers**
Whole numbers used for counting or calculations.

```python
age = 25
quantity = 3
num_of_students = 30

print(f"You are {age} years old")
print(f"You are buying {quantity} items")
print(f"Your class has {num_of_students} students")
```

**Output:**
```
You are 25 years old
You are buying 3 items
Your class has 30 students
```

### **Floats**
Decimal-point numbers used for precision.

```python
price = 10.99
gpa = 3.2
distance = 5.5

print(f"The price is ${price}")
print(f"Your GPA is: {gpa}")
print(f"You ran {distance} kilometers")
```

**Output:**
```
The price is $10.99
Your GPA is: 3.2
You ran 5.5 kilometers
```

---

## 4. **Using f-Strings**
- f-Strings are formatted strings, allowing variable values to be embedded directly into strings.
- Syntax: `f"Your text {variable}"`

---
