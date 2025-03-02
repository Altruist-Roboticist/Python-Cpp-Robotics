# Control Structures

Control structures allow you to control the flow of your program based on certain conditions. In this tutorial, we'll learn about if-else statements and loops in Python.

## If-Else Statements

If-else statements are used to execute a block of code if a condition is true, and another block of code if the condition is false.

### Syntax

```python
if condition:
    # Code to execute if the condition is true
else:
    # Code to execute if the condition is false
```

### Example

```python
age = 18

if age >= 18:
    print("You are an adult.")
else:
    print("You are a minor.")
```

## Elif Statements

You can use `elif` (short for "else if") to check multiple conditions.

### Syntax

```python
if condition1:
    # Code to execute if condition1 is true
elif condition2:
    # Code to execute if condition2 is true
else:
    # Code to execute if none of the conditions are true
```

### Example

```python
score = 85

if score >= 90:
    print("Grade: A")
elif score >= 80:
    print("Grade: B")
elif score >= 70:
    print("Grade: C")
else:
    print("Grade: F")
```

## Loops

Loops allow you to execute a block of code multiple times. Python has two types of loops: `for` loops and `while` loops.

### For Loops

A `for` loop is used to iterate over a sequence (such as a list, tuple, or string).

### Syntax

```python
for item in sequence:
    # Code to execute for each item in the sequence
```

### Example

```python
fruits = ["apple", "banana", "cherry"]

for fruit in fruits:
    print(fruit)
```

### While Loops

A `while` loop is used to execute a block of code as long as a condition is true.

### Syntax

```python
while condition:
    # Code to execute as long as the condition is true
```

### Example

```python
count = 0

while count < 5:
    print(count)
    count += 1
```

## Next Steps

In the next tutorial, we'll learn about functions in Python. Stay tuned!