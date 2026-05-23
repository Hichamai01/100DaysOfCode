
### 1. Python Basics
Today I practiced and verified the core built-in data types in Python using VS Code. I tested how Python identifies different structures using the `type()` function:
* **Numeric Types:** `int` (Integers) and `float` (Floating-point numbers).
* **Strings:** Text manipulation using `str`.
* **Booleans:** Evaluation of expressions resulting in `True` or `False`.
* **Collections:** 
  * `list` (Mutable ordered lists using `[]`)
  * `tuple` (Immutable sequences using `()`)
  * `dict` (Key-value pairs using `{}`)

### 2. Code & Exercises Applied
This is the exact script I wrote, executed, and tested today in my environment:

```python
print(type(100)) # int
print(type(50000)) 
print(type(1))

print(type(12.256)) # float
print(type(2.05549555))
print(type(1.00000000000))

print(type((1, 2, 3, 4))) # tuple
print(type((10, 20, 30, 40)))
print(type((100, 200, 300, 400)))

print(type([1, 2, 3, 4])) # list
print(type([10, 20, 30, 40]))
print(type([100, 200, 300, 400]))

print(type({"one" : 1, "tow" : 2 })) # dict

print(type("Hello Hicham")) # String

print(type(200 == 200)) # bool
print(type(1 == 1))
print(type(1 == 13))
