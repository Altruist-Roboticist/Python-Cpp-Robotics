# Functions

Functions are reusable blocks of code that perform a specific task. In this tutorial, we'll learn how to define and use functions in Python.

## Defining a Function

You can define a function using the `def` keyword, followed by the function name, parentheses, and a colon. The code inside the function is indented.

### Syntax

```python
def function_name(parameters):
    # Code to execute
```

### Example

```python
def greet():
    print("Hello, World!")

# Call the function
greet()
```

## Parameters and Arguments

Functions can accept parameters, which are variables passed to the function. When you call the function, you provide the arguments.

### Example

```python
def greet(name):
    print(f"Hello, {name}!")

# Call the function with an argument
greet("Alice")
```

## Return Values

Functions can return a value using the `return` keyword.

### Example

```python
def add(a, b):
    return a + b

# Call the function and store the result in a variable
result = add(3, 5)
print(result)  # Output: 8
```

## Default Parameters

You can provide default values for parameters. If an argument is not provided, the default value is used.

### Example

```python
def greet(name="World"):
    print(f"Hello, {name}!")

# Call the function without an argument
greet()  # Output: Hello, World!

# Call the function with an argument
greet("Alice")  # Output: Hello, Alice!
```

## Next Steps

In the next tutorial, we'll learn about lists and tuples in Python. Stay tuned!