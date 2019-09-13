# Level 1

So in level 0, we talked about computers processing data. Some of this data happens to 
be the instructions that we use in order to tell the computer what to do.

At a high level, these instructions take the form of programs (which we will get around
to writing soon). Programs are written in a language, which has rules for grammar, syntax
and semantics that you must follow - not unlike English. There are countless programming
languages

Our programming language of choice is Python and we will be getting very used to its rules.

## Python

Python programs are written in text files, typically ending with the file extension *.py*

These programs consist of what are known as **statements** - a unit of code that expresses
some action to be carried out. **Code** is another word for the content of these files,
and you'll hear programmers throw this word around alot.

Statements are not unlike sentences in English; sentences end with a full stop or period.
Similarly, the rules of python say that a statement ends at the end of a line. Whenever
code on a line ends, the statement ends and a new line begins. 

There is a special character known as the newline character (`\n`) that gets placed 
into a file whenever you press the enter key on your keyboard - this is what makes 
the cursor move to new line. Rest assured that it is there, even though you can't 
see it.

Below is a snippet of Python code (don't worry too much about what it means just yet).

```python
hello = "Hello"
world = "World"
hello_world = hello + " " + world
print(hello_world)
```

Based on what we just learned, we know that this code has 4 statements in it. This is 
because there are exactly four (4) lines of code in the snippet.

If you copied this snippet, pasted in into a text file, and gave it a name ending in *.py*,
it would be a completely valid Python program that a computer with Python installed could
execute.

## Handling Data

We keep coming back to this matter of data. As it turns out data is fundamental to 
programming. We just learnt that the very text that comprises our programs is data (input)
to the computer, but the programs themselves also accept and manipulate data.

Since data is so important, programming languages have **data types** to represent various
kinds of data. Python is no exception, and below are the basic data types that can be found in 
Python:

* number
* string
* boolean
* composite data type

Number is exactly what is sounds like. Stuff like 20 and 3.14 and √2 inside a python 
program are represented by a number data type. The number is subdivided into integers, 
floating point and complex numbers and every number in python will fall into one of these.

String is the type that represents character data like the words in this document. In 
Python, strings are surrounded by double (") or single (') quotes.

A boolean is a data type that has only two possible values: `true` and `false`. 

A composite data type is one that is made up of the other basic data types. And it is 
possible to take advantage of this to make your own data types which we will do later. This
is part of what makes programming languages so powerful.

Though not exactly a data type, Python also supports the concept of functions. A function
is a collection of statements that is given a name.

### Constants vs Variables

These data types in their raw form are what we call constant data. They are constant 
because they will never change - the value 3.14 will always be just that 3.14. When the 
computer sees this value, it just understands what it means right away and it knows that it
will never mean anything else.

It is often useful in programs to give meaningful names to these constant values. For 
example, a programmer may want to use the value 3.14 to represent an approximation to pi.
Python allows you to give names to constant values in the form of variables.

A **variable** is a storage location that associates a name to a value. In our example above,
we may create a variable called `pi` that is associated with the value 3.14 for the purposes
of our program. As the name suggests, the benefit that variables provide is that the value
they are associated with is usually not constant - it can change. 