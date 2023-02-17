---
title: "Second Project"
date: 2022-12-29T21:33:05+01:00
draft: false

description: 
cover:
    alt: This is my 2nd alt

tags: [TODO, noTag]

start-date: 2012-02-13
end-date:   2022-11-03

math: true
---
# Latex test

$$x = {-b \pm \sqrt{b^2-4ac} \over 2a}$$

# Basics

* [Documentation](https://docs.python.org/3/)

## Control Flow

### `if` statements

* Form 1: `if`

```bash
if name == 'Homer':
    print('Hi, Homer.')
```

* Form 2: `if/else`

```python
if name == 'Homer':
    print('Hi, Homer.')
else:
    print('You are not Homer')
```

* Form 3: `if/elif/else`

```python
if name == 'Homer':
    print('Hi, Homer.')
elif name == 'Marge':
    print('Hi Marge!')
else:
    print('You are not Homer or Marge')
```

### `for` Loops

The `for` loop iterates over a list, tuple, dictionary, set or string.

```python
for indice in range(5):
    print('Hi, Homer.')
```

### `while` Loops

```python
spam = 0
while spam < 5:
    print('Hi, Homer.')
    spam = spam + 1
```

## Functions / Procedures

Functions and Procedures are specified using the `def` keyword. 

```python
def say_hello(name):
    message = "Hi, {} !".format(name)
    print(message)

say_hello("Homer")
```

### Optional Argument

```python
def say_hello(name="Homer"):
    message = "Hi, {} !".format(name)
    print(message)

say_hello()  # no argument: default value if used for name
say_hello("Marge")
```

### Return Values

```python
def write_message(name):
    message = "Hi, {} !".format(name)
    return message

message = write_message("Homer")
print(message)
```

## Import a library 

You can import a library or jus
``` python 
import math # or
import math as ma # or
from math import pi
```