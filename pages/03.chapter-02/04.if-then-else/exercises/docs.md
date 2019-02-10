---
title: Exercises
date: '06:50 10-02-2019'
taxonomy:
    category:
        - docs
visible: true
author: 'Adrian Gould'
---

# Decision Statement Exercises

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

