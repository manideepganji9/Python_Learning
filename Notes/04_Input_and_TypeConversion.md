# Input Function and Type Conversion

## Input Function

The `input()` function is used to take input from the user.

### Example

```python
name = input("Enter your name: ")
print(name)
```

Note:
- Whatever is entered using `input()` is stored as a string by default.

---

## Taking Number Input

```python
age = input("Enter your age: ")
print(age)
```

Even if you enter `17`, Python stores it as a string.

Check:

```python
age = input("Enter age: ")
print(type(age))
```

Output:

```python
<class 'str'>
```

---

# Type Conversion

Type conversion means converting one data type into another.

## String to Integer

```python
age = int(input("Enter age: "))
print(age)
print(type(age))
```

---

## String to Float

```python
height = float(input("Enter height: "))
print(height)
```

---

## Integer to String

```python
num = 10
num_str = str(num)

print(type(num_str))
```

---

# Why Type Conversion is Needed

Without conversion:

```python
a = input("Enter first number: ")
b = input("Enter second number: ")

print(a + b)
```

Input:

```text
10
20
```

Output:

```text
1020
```

Because both are strings.

Correct way:

```python
a = int(input("Enter first number: "))
b = int(input("Enter second number: "))

print(a + b)
```

Output:

```text
30
```