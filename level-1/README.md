# Level 1

This level covers the following topics:

* Data and data types
* Constants and variables
---

In level 0, we talked about computers processing data. This data includes the very 
instructions that we use in order to tell the computer what to do.

At a high level, these instructions take the form of programs (which we will get around
to writing soon). Programs are written in a language, which has rules for grammar, syntax
and semantics that you must follow - not unlike English. 

There are countless programming languages and our programming language of choice is 
Python. As such, we will need to get acquainted with its rules.

## Python

Python programs are written in text files, typically ending with the file extension *.py*
(e.g. *foo.py*)

The instructions in these programs consist of what are known as **statements** - a unit 
of code that expresses some action to be carried out. **Code** is another word for the 
instructions in a programming language, and you'll hear programmers throw this word around alot.

Statements are not unlike sentences in natural language. For instance according to the 
rules of English, sentences end with a full stop (or period). Similarly, the rules of Python 
prescribe that a statement ends at the end of a line. This mean therefore that whenever code 
on a line ends, the statement has ended and a new statement begins. 

There is a special character known as the newline character (`\n` or `\r\n` depending on your
operating system) that gets placed into a file whenever you press the enter key on your 
keyboard - this is what makes the cursor move to new line. Rest assured that it is there, 
even though you can't see it.

Below is a snippet of Python code (don't worry too much about what it means just yet).

```python
hello = "Hello"
world = "World"
hello_world = hello + " " + world
print(hello_world)
```

Based on what we just learned, we know that this code has 4 statements in it. This is 
because there are exactly four (4) lines of code in the snippet.

If you copied this snippet, pasted it into a text file (and optionally gave it a name ending 
in *.py*), it would be a completely valid Python program that a computer with Python 
installed could execute.

## Handling Data

We keep coming back to this matter of data. As it turns out data is fundamental to 
programming. We just learnt that the very text that comprises our programs is data (input)
to the computer, but the programs themselves also accept and manipulate data.

Since data is so important, programming languages have constructs called **data types** to represent various
kinds of data. Python is no exception, and below are the basic data types that can be found in 
Python:

* number
* string
* boolean
* composite data type

**Number** is exactly what is sounds like. Stuff like 20 and 3.14 inside a python 
program are represented by a number data type. The number is subdivided into integers, 
floating point and complex numbers and every number in python will fall into one of these 
categories.

Here are some examples of numbers in Python:
```python
# integer
2
1024
65536

# floating point
3.14
2.718
0.57721

# complex numbers
2+3j
1+2j
```

> Numbers in Python don't include commas! So one thousand will be 1000 and is an integer

**String** is the type that represents character data like the words in this document. In 
Python, strings are surrounded by double (") or single (') quotes to differentiate them 
from the actual code.

Here are some examples of strings in Python:
```python
"Hello World"
"I am a string"
"I am another string"
'I am a single quoted string'
"""I am a special type of string known as a docstring"""
```

A **boolean** is a data type that has only two possible values: `true` and `false`. If 
you've never heard of booleans before, you may be wondering why it is useful to represent
this in a program. On their own they're not very useful, but they become very powerful
when considering control flow and conditional statements - something we will do later. 

A **composite data type** is one that is made up of the other basic data types. These
are sometimes referred to a **data structures**. A list of numbers is a 
composite data type. It is possible to take advantage of this to make your own data 
types. As it turns out, it is possible to represent all kinds of data using only these
four representations. This is part of what makes programming languages so powerful.

Here are some examples of composite data types in Python:
```python
# list
[1, 2, 3, 4, 5]

# tuple
(1, 2, 3, 4, 5)

# dictionary
{"name": "John Doe", "age": 35}
```

> This code snippet has lines beginning with a #. In Python, any line beginning with a # is ignored by the 
> computer and is not actually a statement. We call these lines comments - they are a programmer's way of leaving 
> messages (to herself or others)

### Constants vs Variables

These data types in their raw form are what we call constant data. They are constant 
because what they mean to the computer will never change - the value 3.14 will always be just 
that: 3.14. When the computer sees that value, it just understands what it means right away and 
there is no ambiguity.

It is often useful for a programmer to use non-constant values. For example, a programmer may want to 
write a program that tracks the running total for a series for numbers. The idea of the total value would
need to be stored somewhere so that it will be available later for another number to be added to it.

A **variable** is that storage location that associates a name with a value. In our example above,
we may create a variable called `total` that is initially the sum of two numbers 3 and 4. 
Whenever the computer sees `total`, it knows there exists a location that stores its value and the computer 
will go there and look it up in order to understand what total means. Later on when the value stored there 
changes, the computer will still be able to understand what total means by doing the same thing - looking in the
stored location. 

## Remarks

We will be using these concepts a lot throughout this series, so don't worry too much if you don't get it right away.
[Let's continue](../level-2).
