---
title: Exercises
date: '01:58 06-02-2019'
taxonomy:
    category:
        - docs
visible: true
author: 'Adrian Gould'
---

! # Overview

This page contains a large number of exercises. 

They are organised into sections that correspond to the section headings in the chapter.

The collection will grow over time, so feel free to come back to practice more!

Each exercise in the chapter will be presented in a format looking like this:

!!!!! **Exercise XX) Exercise Title**
!!!!! **Filename:** ch02-TTTTTTT-XX.py
!!!!! Exercise Details

Name the file that you create using the filename shown. The TTTT will be for a word, or words to identify the section. The XX is a sequential exercise number.

! # The Exercises

## The way of the program

!!!! ### Exercise XX) Exercise Title
!!!! **Filename:** ch02-theway-XX.py
Exercise Details

!!!!! This section needs exercises to be written

## Variables, Booleans & None

!!!! ### Exercise XX) Exercise Title
!!!! **Filename:** ch02-variables-XX.py
Exercise Details

!!!!! This section needs exercises to be written

## Using functions

!!!! ### Exercise XX) Exercise Title
!!!! **Filename:** ch02-builtin-XX.py
Exercise Details

!!!!! This section needs exercises to be written

## Decision Statements

!!!! ### Exercise 1. Fix the errors
!!!! **Filename:** ch02-decisions-01.py

This program contains several problems. 

Copy-paste it to a file, then try to run it, fix the errors you got, try to run it again and keep going until it works.

    ```python
    print(Hello!)
    something == input('Enter something: )
    print('You entered:' something)
    ```

!!!! ### Exercise 2. Fix the errors
!!!! **Filename:** ch02-decisions-02.py

Fix this program the same way:

    ```python
    print('Hello!')
    something = input("Enter something: ")
    if something = 'hello':
        print("Hello for you too!")

    elif something = 'hi'
        print('Hi there!')
    else:
        print("I don't know what," something, "means.")
    ```

!!!! ### Exercise 3. Printing Words
!!!! **Filename:** ch02-decisions-03.py

Write a program into a file that asks the user to write a word and then prints that word 1000 times.

For example, if the user enters `hi` the program would reply `hihihihihihihihi` ...

!!!! ### Exercise 4. Printing Words with Spaces
!!!! **Filename:** ch02-decisions-04.py

Copy your code from the previous exercise and save it in the new file, as given above.

Now modify the program so it adds spaces between the words, to produce output that is like `hi hi hi hi` ...

!!!! ### Exercise 5. Printing Two Words
!!!! **Filename:** ch02-decisions-05.py

Make something that asks the user to enter two words, and prints 1000 of each with spaces in between. 

For example, if the user enters `hello` and `hi` the program would print  `hello hi hello hi hello hi hello hi hello hi` ...

!!!! ### Exercise 6. Access Denied
!!!! **Filename:** ch02-decisions-06.py

Make a program that asks for a password and prints one of the following depending on the situation following it:

* `Welcome!` when the user entered the correct password
* `Access denied` when the user entered an incorrect password
* `You didn't enter anything` or nothing at all when the user pressed **Enter** without typing anything.



## String Methods

!!!! ### Exercise 01) Fixer-upper
!!!! **Filename:** ch02-strings-01.py

Fix this program. Copy and paste the copde into your python editor and fix the program.

    ```python
    print("Hello!")
    word1 = input("Enter something: ")
    word2 = input("Enter another thing: ")
    word3 = input "Enter a third thing: "
    word4 = input("And yet another thing: ")
    print("You entered " + word1  ,   word2 + ", " + word3 + " and " + word4 + ".")
    ```

!!!! ### Exercise 02) LOUD text
!!!! **Filename:** ch02-strings-02.py

This program is supposed to say something loudly. Fix it.

    ```python
    message = input("What do you want me to say? ")
    message.upper
    print(message, "!!!")
    print(message, "!!!")
    print(message, "!!!")
    ```
    


!!!! ### Exercise XX) Exercise Title
!!!! **Filename:** ch02-strings-XX.py
Exercise Details



## Lists and Tuples

!!!! ### Exercise 01) Fixer-upper I
!!!! **Filename:** ch02-lists-01.py

Fix this program:

    ```python
    namelist = ('wub_wub', 'RubyPinch', 'go|dfish', 'Nitori')
    namelist.append('pb122')
    if 'pb122' in namelist:
        print("Now I know pb122!")
    ```

!!!! ### Exercise 02) Fixer-upper II
!!!! **Filename:** ch02-lists-02.py

Fix this program.

    ```python
    print("Hello!")
    name = input("Enter your name: "),
    print("Your name is " + name + ".")
    ```

!!!! ### Exercise 03) Fixer-upper III
!!!! **Filename:** ch02-lists-03.py

Fix this program.

    ```python
    namelist = ['wub_wub', 'RubyPinch', 'go|dfish', 'Nitori']
    namelist = namelist.extend('theelous3')
    if input("Enter your name: ") in namelist:
        print("I know you!")
    else:
        print("I don't know you.")
    ```
    


## Loops

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


## Zip and Enumerate


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

## Dictionaries

!!!! ### Exercise XX) Exercise Title
!!!! **Filename:** ch02-dictionaries-XX.py
Exercise Details

!!!!! This section needs exercises to be written

## Functions

**There are many things to learn about functions, and I don't expect
you to learn everything at once.** However, there are also many free
exercises about defining functions you can do.

!!!! ### Exercise 01) Code Malfunction
!!!! **Filename:** ch02-userfunctions-01.py

What's wrong with this code?

    ```python
    def ask_name():
        name = input("Enter your name: ")

    ask_name()
    print("Your name is", name)
    ```

!!!! ### Exercise 02) Code Malfunction II
!!!! **Filename:** ch02-userfunctions-02.py

How about this code?

    ```python
    def get_greeting():
        return "Hello World!"

    print(get_greeting)
    ```

!!!! ### Exercise 03) Exercise Title
!!!! **Filename:** ch02-userfunctions-03.py

Why does this print None after greeting the world?

    ```python
    def greet(target):
        print("Hello", target)

    print(greet("World"))
    ```



!!!!! This section needs more exercises to be written

## Writing Larger Programs


!!!! ### Exercise XX) Exercise Title
!!!! **Filename:** ch02-larger-XX.py
Exercise Details

!!!!! This section needs exercises to be written

## What is True?


!!!! ### Exercise XX) Exercise Title
!!!! **Filename:** ch02-true-XX.py
Exercise Details

!!!!! This section needs exercises to be written

## Files

!!!! ### Exercise XX) Exercise Title
!!!! **Filename:** ch02-textfiles-XX.py
Exercise Details

!!!!! This section needs exercises to be written