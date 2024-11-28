# Python Basics: Inputs
This document summarizes how to use Python's `input()` function, handle typecasting, and solve basic exercises.

---

## 6. **Input Function**
- The `input()` function allows user interaction by accepting data from the keyboard.
- Data entered via `input()` is always returned as a **string**.

### Example:
```python
name = input("What is your name?: ")
age = input("How old are you?: ")

print(f"Hello {name}!")
print(f"You are {age} years old!")
```

---

## 7. **Common Error with `input()`**
Attempting arithmetic with inputs without typecasting causes errors because inputs are strings.

### Example: Incorrect Use
```python
age = input("How old are you?: ")
age = age + 1  # Causes a TypeError
```

### Fix: Convert Input to Integer
```python
age = int(input("How old are you?: "))  # Convert string to integer
age = age + 1
print(f"You will be {age} years old next year!")
```

---

## 8. **Exercises**

### **Exercise 1: Rectangle Area Calculator**
Calculate the area of a rectangle based on user input.

#### Code:
```python
length = float(input("Enter the length: "))
width = float(input("Enter the width: "))
area = length * width
print(f"The area is: {area} cm²")
```

#### Output:
```
Enter the length: 5
Enter the width: 4
The area is: 20.0 cm²
```

---

### **Exercise 2: Shopping Cart Program**
Calculate the total cost of items in a shopping cart.

#### Code:
```python
item = input("What item would you like to buy?: ")
price = float(input("What is the price?: "))
quantity = int(input("How many would you like?: "))
total = price * quantity

print(f"You have bought {quantity} x {item}(s)")
print(f"Your total is: ${total}")
```

#### Output:
```
What item would you like to buy?: Apple
What is the price?: 0.5
How many would you like?: 4
You have bought 4 x Apple(s)
Your total is: $2.0
```

---

### Notes:
- Always convert input to the appropriate data type (`int`, `float`, etc.) when performing calculations.
- Use `f-strings` for easy formatting of output.

