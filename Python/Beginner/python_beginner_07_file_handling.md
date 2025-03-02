# File Handling

File handling is an essential part of any programming language. In this tutorial, we'll learn how to read from and write to files in Python.

## Opening a File

You can open a file using the `open()` function. The `open()` function takes two arguments: the file name and the mode in which you want to open the file.

### Modes

- `'r'`: Read mode (default). Opens the file for reading.
- `'w'`: Write mode. Opens the file for writing (creates a new file or truncates an existing file).
- `'a'`: Append mode. Opens the file for appending (creates a new file if it doesn't exist).
- `'b'`: Binary mode. Opens the file in binary mode.

### Example

```python
file = open("example.txt", "r")
```

## Reading from a File

You can read the contents of a file using the `read()` method.

### Example

```python
file = open("example.txt", "r")
content = file.read()
print(content)
file.close()
```

### Reading Line by Line

You can read a file line by line using the `readline()` method or by iterating over the file object.

### Example

```python
file = open("example.txt", "r")

# Using readline() method
line = file.readline()
while line:
    print(line, end="")
    line = file.readline()

file.close()
```

```python
file = open("example.txt", "r")

# Iterating over the file object
for line in file:
    print(line, end="")

file.close()
```

## Writing to a File

You can write to a file using the `write()` method.

### Example

```python
file = open("example.txt", "w")
file.write("Hello, World!\n")
file.write("This is a new line.")
file.close()
```

### Appending to a File

You can append to a file using the `write()` method in append mode.

### Example

```python
file = open("example.txt", "a")
file.write("\nThis is an appended line.")
file.close()
```

## Closing a File

It's important to close a file after you're done using it to free up system resources. You can close a file using the `close()` method.

### Example

```python
file = open("example.txt", "r")
# Perform file operations
file.close()
```

## Using `with` Statement

You can use the `with` statement to automatically close a file when you're done with it.

### Example

```python
with open("example.txt", "r") as file:
    content = file.read()
    print(content)
```

## Next Steps

In the next tutorial, we'll learn about basic robotics concepts in Python, such as controlling servos and reading sensors. Stay tuned!