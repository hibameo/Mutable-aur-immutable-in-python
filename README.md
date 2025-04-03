# Mutable vs Immutable in Python

## Mutable Data Types
Mutable data types are those that can be changed after their creation. Modifications such as adding, removing, or updating elements happen in place without changing the memory address.

### Examples of Mutable Data Types:
1. **List (`list`)**
2. **Dictionary (`dict`)**
3. **Set (`set`)**
4. **Bytearray (`bytearray`)**

### Example:
```python
# List (Mutable)
my_list = [1, 2, 3]
my_list.append(4)  # Modifies the original list
print(my_list)  # Output: [1, 2, 3, 4]
```

---

## Immutable Data Types
Immutable data types cannot be changed after their creation. Any modification results in the creation of a new object.

### Examples of Immutable Data Types:
1. **Integer (`int`)**
2. **Float (`float`)**
3. **String (`str`)**
4. **Tuple (`tuple`)**
5. **Frozen Set (`frozenset`)**
6. **Bytes (`bytes`)**

### Example:
```python
# String (Immutable)
my_str = "Hello"
new_str = my_str + " World"  # Creates a new string
print(new_str)  # Output: "Hello World"
```

---

## `try` Keyword
The `try` keyword in Python is used for exception handling. It allows you to test a block of code for errors.

### Example:
```python
try:
    x = 5 / 0
except ZeroDivisionError:
    print("Cannot divide by zero!")
```

---

## Summary
- **Mutable:** Can be changed after creation (e.g., List, Dict, Set)
- **Immutable:** Cannot be changed after creation (e.g., Int, String, Tuple)
- **`try` is a keyword** used for error handling in Python.
