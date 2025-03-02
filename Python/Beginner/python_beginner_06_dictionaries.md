# Dictionaries

Dictionaries are used to store data in key-value pairs. In this tutorial, we'll learn about dictionaries in Python.

## Creating a Dictionary

A dictionary is created using curly braces `{}` and contains key-value pairs separated by commas.

### Example

```python
person = {
    "name": "Alice",
    "age": 25,
    "city": "New York"
}
print(person)  # Output: {'name': 'Alice', 'age': 25, 'city': 'New York'}
```

## Accessing Values

You can access the value associated with a specific key using square brackets `[]`.

### Example

```python
person = {
    "name": "Alice",
    "age": 25,
    "city": "New York"
}
print(person["name"])  # Output: Alice
print(person["age"])   # Output: 25
print(person["city"])  # Output: New York
```

## Modifying Values

You can modify the value associated with a specific key by assigning a new value to the key.

### Example

```python
person = {
    "name": "Alice",
    "age": 25,
    "city": "New York"
}
person["age"] = 26
print(person)  # Output: {'name': 'Alice', 'age': 26, 'city': 'New York'}
```

## Adding Key-Value Pairs

You can add a new key-value pair to a dictionary by assigning a value to a new key.

### Example

```python
person = {
    "name": "Alice",
    "age": 25,
    "city": "New York"
}
person["email"] = "alice@example.com"
print(person)  # Output: {'name': 'Alice', 'age': 25, 'city': 'New York', 'email': 'alice@example.com'}
```

## Removing Key-Value Pairs

You can remove a key-value pair from a dictionary using the `del` keyword.

### Example

```python
person = {
    "name": "Alice",
    "age": 25,
    "city": "New York"
}
del person["age"]
print(person)  # Output: {'name': 'Alice', 'city': 'New York'}
```

## Next Steps

In the next tutorial, we'll learn about file handling in Python. Stay tuned!