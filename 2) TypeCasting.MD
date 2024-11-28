
## **Typecasting**
Typecasting is the process of converting a variable from one data type to another. This can be done using built-in functions like `str()`, `int()`, `float()`, and `bool()`.

### Example: Checking Variable Type
```python
name = "Bro Code"
age = 25
gpa = 3.2
is_student = True

print(type(age))  # Outputs the data type of the 'age' variable
```

**Output:**
```
<class 'int'>
```

---

### Example: Changing Data Types
You can change the type of a variable to fit specific needs. 

#### Convert `age` to a `float`:
```python
age = float(age)
print(age)       # Converts age from an integer to a float
print(type(age)) # Verifies the data type
```

**Output:**
```
25.0
<class 'float'>
```

#### Convert `age` to a `string`:
```python
age = str(age)
print(type(age)) # Converts age to a string
```

**Output:**
```
<class 'str'>
```

#### Convert `name` to a `boolean`:
```python
name = bool(name)
print(name)      # Converts a non-empty string to True
```

**Output:**
```
True
```

---

## Notes on Typecasting:
- **`str()`**: Converts a variable to a string.
- **`int()`**: Converts a variable to an integer (if applicable).
- **`float()`**: Converts a variable to a floating-point number.
- **`bool()`**: Converts a variable to a boolean (`True` for non-empty values or non-zero numbers, otherwise `False`).

