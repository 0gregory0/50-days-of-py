# 2. Strings
---

Strings in Python are the way we work with text. Words, sentences, paragraphs, and
even entire files are read into and manipulated via strings. Because so much of our
work revolves around text, it’s no surprise that strings are one of the most common
data types.

Strings are immutable data types. They can also be called data structures because they
store a sequence of data that can be iterated over. This chapter includes exercises
designed to help you work with strings in a variety of ways. The more familiar you are
with Python’s string manipulation techniques, the easier it will be to work with text.

## Prerequisites
---

| Concept | What is it? | Example | To learn more |
| --- | --- | --- | --- |
| ```in``` | Operator for searching in a sequence | ```'a' in 'abcd'``` | http://mng.bz/yy2G |
| Slice | Retrieves a subset of elements from a sequence | ``` 'abcdefg'[1:7:2] # returns 'bdf'``` | http://mng.bz/MdW7 |
| ```str.split``` | Breaks strings apart, returning a list | ```'abc def ghi'.split() # returns ['abc', 'def', 'ghi']``` | http://mng.bz/aR4z |
| ```str.join``` | Combines strings to create a new one | ```'*'.join(['abc', 'def', 'ghi']) # returns 'abc*def*ghi'``` | http://mng.bz/gyYl |
| ```list.append``` | Adds an element to a list | ```mylist.append('hello')``` | http://mng.bz/aR7z |
| ```sorted``` | Returns a sorted list, based on an input sequence | ```sorted([10, 30, 20]) # returns [10, 20, 30]``` | http://mng.bz/pBEG |
| Iterating over files | Opens a file and iterates over its lines one at a time | ```for one_line in open(filename):``` | http://mng.bz/OMAn |