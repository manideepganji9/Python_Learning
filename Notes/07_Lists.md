# Lists in Python

## What is a List?

A list is used to store multiple values in a single variable.

Example:

```python
marks = [95, 87, 76, 90]
```

Lists can store different data types.

```python
student = ["Manideep", 17, 92.5, True]
```

---

# Accessing List Elements

```python
fruits = ["Apple", "Banana", "Mango"]

print(fruits[0])
print(fruits[1])
```

Output:

```text
Apple
Banana
```

---

# List Slicing

```python
numbers = [10, 20, 30, 40, 50]

print(numbers[1:4])
```

Output:

```text
[20, 30, 40]
```

---

# Changing Values

```python
fruits = ["Apple", "Banana", "Mango"]

fruits[1] = "Orange"

print(fruits)
```

Output:

```text
['Apple', 'Orange', 'Mango']
```

---

# List Methods

## append()

Adds an item at the end.

```python
numbers = [1, 2, 3]

numbers.append(4)

print(numbers)
```

Output:

```text
[1, 2, 3, 4]
```

---

## sort()

Sorts the list.

```python
numbers = [5, 2, 8, 1]

numbers.sort()

print(numbers)
```

Output:

```text
[1, 2, 5, 8]
```

---

## reverse()

Reverses the list.

```python
numbers.reverse()
```

---

## insert()

Adds an item at a specific position.

```python
numbers.insert(1, 100)
```

---

## remove()

Removes a specific value.

```python
numbers.remove(100)
```

---

## pop()

Removes item using index.

```python
numbers.pop(0)
```