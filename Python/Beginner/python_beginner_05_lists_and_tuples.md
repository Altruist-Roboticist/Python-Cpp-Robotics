# Lists and Tuples

Lists and tuples are used to store collections of items. In this tutorial, we'll learn about lists and tuples in Python.

## Lists

A list is a collection of items that are ordered and changeable. Lists are defined using square brackets `[]`.

### Example

```python
fruits = ["apple", "banana", "cherry"]
print(fruits)  # Output: ['apple', 'banana', 'cherry']
```

### Accessing Items

You can access items in a list using their index. The index starts at 0 for the first item.

### Example

```python
fruits = ["apple", "banana", "cherry"]
print(fruits[0])  # Output: apple
print(fruits[1])  # Output: banana
print(fruits[2])  # Output: cherry
```

### Modifying Items

You can modify items in a list by assigning a new value to a specific index.

### Example

```python
fruits = ["apple", "banana", "cherry"]
fruits[1] = "blueberry"
print(fruits)  # Output: ['apple', 'blueberry', 'cherry']
```

### Adding Items

You can add items to a list using the `append()` method.

### Example

```python
fruits = ["apple", "banana", "cherry"]
fruits.append("orange")
print(fruits)  # Output: ['apple', 'banana', 'cherry', 'orange']
```

### Removing Items

You can remove items from a list using the `remove()` method.

### Example

```python
fruits = ["apple", "banana", "cherry"]
fruits.remove("banana")
print(fruits)  # Output: ['apple', 'cherry']
```

## Tuples

A tuple is a collection of items that are ordered and unchangeable. Tuples are defined using parentheses `()`.

### Example

```python
fruits = ("apple", "banana", "cherry")
print(fruits)  # Output: ('apple', 'banana', 'cherry')
```

### Accessing Items

You can access items in a tuple using their index.

### Example

```python
fruits = ("apple", "banana", "cherry")
print(fruits[0])  # Output: apple
print(fruits[1])  # Output: banana
print(fruits[2])  # Output: cherry
```

### Unpacking Tuples

You can unpack a tuple into individual variables.

### Example

```python
fruits = ("apple", "banana", "cherry")
(a, b, c) = fruits
print(a)  # Output: apple
print(b)  # Output: banana
print(c)  # Output: cherry
```

## Next Steps

In the next tutorial, we'll learn about dictionaries in Python. Stay tuned!