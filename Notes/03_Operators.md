# Operators in Python

Operators are symbols used to perform operations on values and variables.

---

# 1. Arithmetic Operators

Used for mathematical calculations.

| Operator | Meaning | Example |
|----------|----------|----------|
| + | Addition | 5 + 2 = 7 |
| - | Subtraction | 5 - 2 = 3 |
| * | Multiplication | 5 * 2 = 10 |
| / | Division | 5 / 2 = 2.5 |
| % | Modulus (Remainder) | 5 % 2 = 1 |
| ** | Exponent (Power) | 5 ** 2 = 25 |

Example:

```python
a = 5
b = 2

print(a + b)
print(a - b)
print(a * b)
print(a / b)
print(a % b)
print(a ** b)
```

---

# 2. Relational Operators

Used to compare values.

| Operator | Meaning |
|----------|----------|
| == | Equal to |
| != | Not equal to |
| > | Greater than |
| < | Less than |
| >= | Greater than or equal to |
| <= | Less than or equal to |

Example:

```python
a = 20
b = 14

print(a == b)
print(a > b)
print(a != b)
```

Output:

```python
False
True
True
```

---

# 3. Assignment Operators

Used to assign values.

```python
a = 10

a += 5
print(a)

a -= 2
print(a)

a *= 3
print(a)
```

---

# 4. Logical Operators

Used with Boolean values.

## NOT

```python
print(not True)
print(not False)
```

## AND

Returns True if both conditions are True.

```python
print(True and True)
print(True and False)
```

## OR

Returns True if at least one condition is True.

```python
print(True or False)
print(False or False)
```