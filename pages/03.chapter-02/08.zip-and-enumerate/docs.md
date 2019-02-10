---
title: 'Zip and Enumerate'
date: '13:41 31-01-2019'
taxonomy:
    category:
        - docs
visible: true
author: 'Adrian Gould'
---

# Trey Hunner: zip and enumerate

Now we know how [for loops](loops.md#for-loops) work in Python. But for loops aren't limited to printing each item in a list, they can do a lot more.

## Python assignment trick

To be able to understand for loop tricks we need to first know assigning values to multiple variables at once. It works like this:

```python
>>> a, b = 1, 2
>>> a
1
>>> b
2
>>>
```

### Assignment trick with list and tuple

We can use `()` and `[]` around these values however we want and everything will still work the same way. `[]` creates a list, and `()` creates a tuple.

```python
>>> [a, b] = (1, 2)
>>> a
1
>>> b
2
>>>
```

### Single sided list or tuple trick

We can also have `[]` or `()` on one side but not on the other side.

```python
>>> (a, b) = 1, 2
>>> a
1
>>> b
2
>>>
```

Python created a tuple automatically.

```python
>>> 1, 2
(1, 2)
>>>
```

### Looping over a list with value pairs

If we're for looping over a list with pairs of values in it we could do this:

```python
>>> items = [('a', 1), ('b', 2), ('c', 3)]
>>> for pair in items:
...     a, b = pair
...     print(a, b)
...
a 1
b 2
c 3
>>>
```

Or we can tell the for loop to unpack it for us.

```python
>>> for a, b in items:
...     print(a, b)
...
a 1
b 2
c 3
>>>
```

## Trey Hunner Tutorial

Now you're ready to read [this awesome looping tutorial](http://treyhunner.com/2016/04/how-to-loop-with-indexes-in-python/).

Read it now, then come back here and do the exercises.
