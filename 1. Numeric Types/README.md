# Numeric Types
---

Whether you’re calculating salaries, bank interest, or cellular frequencies, it’s hard
to imagine a program that doesn’t use numbers in one way or another. Python has
three different numeric types: int, float, and complex. For most of us, it’s enough
to know about (and work with) int (for whole numbers) and float (for numbers
with a fractional component).

Numbers are not only fundamental to programming, but also give us a good
introduction to how a programming language operates. Understanding how variable assignment and function arguments work with integers and floats will help you
to reason about more complex types, such as strings, tuples, and dicts.

This chapter contains exercises that work with numbers, as inputs and as outputs. Although working with numbers can be fairly basic and straightforward, converting between them, and integrating them with other data types, can sometimes
take time to get used to.

## Prerequisites
---

| Concept | What is it | Example | To Learn More |
| -------- | -------- | -------- | -------- |
| ```random``` | A module for generating random numbers and selecting random elements | ```number = random.randint(1, 100)``` | https://docs.python.org/3/library/random.html |
| Comparisons |  Operators for comparing values | ```x < y``` | https://docs.python.org/3/reference/expressions.html#comparisons |
f-strings | Strings into which expressions can be interpolated | ```f"My name is {name} and I am {age} years old"``` | https://peps.python.org/pep-0498/ |
```for``` loops | Iterates over the elements of an iterable | ```for i in range (1, 11): print(i)``` | https://docs.python.org/3/tutorial/controlflow.html#for-statements |
```enumerate``` | Helps us to number elements of iterables | ```for index, item in enumerate('abc'): print(f'{index}:{item}')``` | https://docs.python.org/3/library/functions.html#enumerate |