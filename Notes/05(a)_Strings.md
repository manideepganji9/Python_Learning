# Strings in Python

## What is a String?

A string is a sequence of characters enclosed in quotes.

Examples:

```python
name = "Manideep"
city = 'Hyderabad'
```

---

# Escape Sequences

## New Line (\n)

```python
print("Hello\nWorld")
```

Output:

```text
Hello
World
```

---

## Tab Space (\t)

```python
print("Python\tProgramming")
```

Output:

```text
Python    Programming
```

---

# String Concatenation

Used to join strings.

```python
first = "Hello"
second = "World"

print(first + second)
```

Output:

```text
HelloWorld
```

With space:

```python
print(first + " " + second)
```

Output:

```text
Hello World
```

---

# Length of String

Use len() function.

```python
name = "Manideep"

print(len(name))
```

Output:

```text
8
```

---

# String Indexing

Each character has an index.

```python
name = "Python"
```

| Character | P | y | t | h | o | n |
|------------|---|---|---|---|---|---|
| Index | 0 | 1 | 2 | 3 | 4 | 5 |

Example:

```python
name = "Python"

print(name[0])
print(name[3])
```

Output:

```text
P
h
```

---

# String Slicing

Syntax:

```python
string[start:end]
```

End index is not included.

Example:

```python
name = "Python"

print(name[0:3])
```

Output:

```text
Pyt
```

Example:

```python
print(name[2:6])
```

Output:

```text
thon
```

---

# Negative Indexing

```python
name = "Python"

print(name[-1])
```

Output:

```text
n
```

Last character is -1.