# String Functions

## endswith()

Checks whether a string ends with a given value.

```python
name = "python"

print(name.endswith("on"))
```

Output:

```text
True
```

---

## capitalize()

Capitalizes first letter.

```python
name = "python"

print(name.capitalize())
```

Output:

```text
Python
```

---

## replace()

Replaces text.

```python
text = "I love Python"

print(text.replace("Python", "Java"))
```

Output:

```text
I love Java
```

---

## find()

Finds index of first occurrence.

```python
name = "Python"

print(name.find("t"))
```

Output:

```text
2
```

Returns -1 if not found.

---

## count()

Counts occurrences.

```python
text = "apple apple banana"

print(text.count("apple"))
```

Output:

```text
2
```