---
title: Exercises
date: '06:53 10-02-2019'
taxonomy:
    category:
        - docs
visible: true
author: 'Adrian Gould'
---

# Loop Exercises

!!!! ### Exercise 01) Number up
!!!! **Filename:** ch02-loop-01.py

This code is supposed to print the numbers 1,2,3,4,5. 

Fix it.

    ```python
    things = str([1, 2, 3, 4, 5])
    for thing in things:
        print(thing)
    ```

!!!! ### Exercise 03) Fix the numbers
!!!! **Filename:** ch02-loop-02.py

This code is supposed to print `[1, 2, 3, 4, 5, 6]`. 

Fix it without changing the `before` list.

    ```python
    before = [[1, 2], [3, 4], [5, 6]]
    after = []
    for number in before:
        after.append(number)
    print(after)
    ```

!!!! ### Exercise 03) Integer Lists
!!!! **Filename:** ch02-loop-03.py
This program is supposed to convert everything in a list to integers and then calculate their sum. 

It should print 6 because `1 + 2 + 3` is 6.

Fix the program.

    ```python
    input = ['1', '2', '3']

    for string in input:
        numbers = []
        numbers.append(int(string))

    result = 0
    for n in numbers:
        result + n
    print("their sum is", result)
    ```

!!!! ### Exercise 04) Number List II
!!!! **Filename:** ch02-loop-XX.py

This program is supposed to print `[1, 2, 3]`. 

Fix it.

    ```python
    numbers = ['1', '2', '3']
    for number in numbers:
        number = int(number)
    print(numbers)
    ```
