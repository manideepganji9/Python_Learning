# Conditional Statements in Python

Conditional statements help a program make decisions.

---

# if Statement

Syntax:

```python
if (condition):
    # code
```

Example:

```python
age = 18

if (age >= 18):
    print("You can vote")
```

Output:

```text
You can vote
```

---

# if-else Statement

Syntax:

```python
if (condition):
    # code
else:
    # code
```

Example:

```python
age = 16

if (age >= 18):
    print("You can vote")
else:
    print("You cannot vote")
```

Output:

```text
You cannot vote
```

---

# elif Statement

Used when there are multiple conditions.

Example:

```python
marks = 75

if (marks >= 90):
    print("Grade A")
elif (marks >= 75):
    print("Grade B")
else:
    print("Grade C")
```

Output:

```text
Grade B
```

---

# Nested if

An if statement inside another if statement.

Example:

```python
age = 20
has_id = True

if (age >= 18):
    if (has_id):
        print("Entry allowed")
```

Output:

```text
Entry allowed
```

---

# Important Points

1. Indentation is mandatory in Python.
2. Conditions return True or False.
3. elif means "else if".
4. Only one block executes.