# Variables and Data Types

In this tutorial, we'll learn about variables and data types in Python. Variables are used to store data, and data types define the type of data that can be stored in a variable.

## Variables

A variable is a name that refers to a value. You can think of it as a container that holds data. In Python, you don't need to declare a variable before using it. You just assign a value to a variable using the `=` operator.

### Example

```python
x = 5
y = "Hello, World!"
```

In the example above, `x` is a variable that holds the integer value `5`, and `y` is a variable that holds the string value `"Hello, World!"`.

## Data Types

Python has several built-in data types. Here are some of the most commonly used ones:

1. **Integers**: Whole numbers, e.g., `5`, `-3`, `42`.
2. **Floats**: Numbers with decimal points, e.g., `3.14`, `-0.001`, `2.0`.
3. **Strings**: Sequences of characters, e.g., `"Hello, World!"`, `'Python'`.
4. **Booleans**: Logical values, `True` or `False`.

### Example

```python
age = 25          # Integer
height = 5.9      # Float
name = "Alice"    # String
is_student = True # Boolean
```

## Type Conversion

You can convert between different data types using built-in functions. Here are some examples:

1. `int()`: Converts a value to an integer.
2. `float()`: Converts a value to a float.
3. `str()`: Converts a value to a string.

### Example

```python
x = 5          # Integer
y = 3.14       # Float
z = "42"       # String

# Convert float to integer
a = int(y)     # a = 3

# Convert integer to float
b = float(x)   # b = 5.0

# Convert string to integer
c = int(z)     # c = 42

# Convert integer to string
d = str(x)     # d = "5"
```

## Next Steps

In the next tutorial, we'll learn about control structures in Python, such as if-else statements and loops. Stay tuned!