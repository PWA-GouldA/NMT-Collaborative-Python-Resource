---
title: Exercises
date: '06:54 10-02-2019'
taxonomy:
    category:
        - docs
visible: true
author: 'Adrian Gould'
---

# Zip and Enumerate Exercises


!!!! ### Exercise 01) User Input and Display
!!!! **Filename:** ch02-zipenum-01.py

Create a program that works like this. 

Here I entered everything    after the `>` prompt that the program displayed.

    ```
    Enter something, and press Enter without typing anything when you're done.
    >hello there
    >this is a test
    >it seems to work
    >
    Line 1 is: hello there
    Line 2 is: this is a test
    Line 3 is: it seems to work
    ```

!!!! ### Exercise 02) Letters
!!!! **Filename:** ch02-zipenum-02.py

2. Create a program that prints all letters from *A* to *Z* and *a* to *z*   next to each other:

    ```
    A a
    B b
    C c
    ...
    X x
    Y y
    Z z
    ```

    Start your program like this:

    ```python
    uppercase = 'ABCDEFGHIJKLMNOPQRSTUVWXYZ'
    lowercase = 'abcdefghijklmnopqrstuvwxyz'
    ```

    **Hint:** how do strings behave with `zip`? 
    Try it out on the  `>>>` prompt and see.


!!!! ### Exercise 03) Letters and Indexes
!!!! **Filename:** ch02-zipenum-03.py

Copy the code from the previous exercise into a new file (name given above).

Can you change the code to make it print the indexes also?

    ```
    1 A a
    2 B b
    3 C c
    ...
    24 X x
    25 Y y
    26 Z z
    ```
