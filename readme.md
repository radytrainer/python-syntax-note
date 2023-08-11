## Python basic syntax note

### 1. Variable
- number = 0 `// integer variable`
- text = "Hello, world!" `// string variable`
- hasNumber = True `// boolean variable`
- average = 12.3 `// float variable`

### 2. Conditional expression
- `if` condition
```python
if condition:
    // your code here

# Example
if 5 < 10:
    print("Yes")
```
- `if - else` conditions (Work only one block)
```python
if condition:
    // your code here
else:
    // your code here

# Example
if 3 < 4:
    print("Yes")
else:
    print("No")
```
- `if - elif` conditions (Work only one block)
```python
if condition:
    // your code here
elif condition:
    // your code here

# Example
if 3 < 4:
    print("Yes")
elif 4 < 3:
    print("No")
```
- `if - elif - elif ... - else` conditions (Work only one block)
```python
if condition:
    // your code here
elif condition:
    // your code here
elif condition:
    // your code here
...
else:
    // your code here

# Example
if 3 < 4:
    print("Yes")
elif 4 < 3:
    print("No")
elif 5 < 3:
    print("Okay")
elif 6 < 3:
    print("Sorry")
else:
    print("Goodbye")
```
- `if - if` conditions (Work both block if condition is `true`)
```python
if condition:
    // your code here
if condition:
    // your code here

# Example
if 3 < 4:
    print("Yes")
if 4 < 3:
    print("No")
```
- Nesting `if` condition
```python
if condition:
    if condition:
        // your code here
    else:
        // your code here
else:
    if condition:
        // your code here
# Example
if 3 < 4:
    if 3 == 4:
        print("Yes")
    else:
        print("No")
else:
    if 3 < 7:
        print("Okay")
```

### 3. Loop
-  `for` loop by default variable in for loop start from `0` and in range must be integer value
```python
for variable in range(integer_value):
    // your code here

# Example
for i in range(3):
    print(i)
# Output
0
1
2
```
- `while` loop always secute while condition is true
```python
while condition:
    // your code here

# Example
i = 0
while i < 3:
    print(i)
    i = i + 1
# Output
0
1
2
```
### 4. String function allow to use in algorithm course
- `len()` returns number of characters
```python
print(len("hello"))
# output
5
```
- `str()` returns string
```python
print(str(100))
#output
"100"
```
- `upper()` returns string with uppercase characters
```python
text = "Hello".upper()
print(text)
# output
HELLO
```
- `lower()` returns string with lowercase characters
```python
text = "HELLO".lower()
print(text)
# output
hello
```
- `isupper()` returns  `True` if string is uppercase otherwise `False`
```python
hasUpper1 = "A".isupper()
hasUpper2 = "b".isupper()
print(hasUpper1)
print(hasUpper2)
# output
True
False
```
- `islower()` returns `True` if string is lowercase otherwise `False`
```python
hasLower1 = "A".islower()
hasLower2 = "b".islower()
print(hasLower1)
print(hasLower2)
# output
False
True
```
- `isnumeric()` returns `True` if string is type of integer otherwise `False`
```python
hasNumber1 = "A".isnumeric()
hasNumber2 = "3".isnumeric()
print(hasNumber1)
print(hasNumber2)
# output
False
True
```
