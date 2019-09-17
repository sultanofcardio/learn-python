# Level 2

This level covers the following topics:

* Statements and expressions
---

## Statements

So far, we know that every line in a valid Python program is an individual statement. Of these, there are quite a few
different kinds. The different kinds of statements in Python that we'll be considering are listed below:

* Expression
* Assignment
* Pass
* Delete
* Return
* Raise
* Break
* Continue
* Import

### Expression

An **expression** is a statement comprising a sequence of elements that can be reduced to a value in one of the data 
types listed in level 1. Think of this like an algebraic expression - by applying some simple rules to such an 
expression you may obtain a simpler form of the expression, sometimes even reducing it to a single number.

The simplest expression is the atom. An **atom** is any constant value, such as a number or string. These raw values
are themselves expressions and, transitively, statements. An atom may also be a variable, as they stand in for constant
values. We have already seen examples of this expression in level 1
```python
# integer
2
1024
65536
```

When an atom is a constant value, it is called a literal. Atoms are the building blocks of all other expressions.

Below is an example of an arithmetic expression, using one of the arithmetic operators
```python
5 + 10
```
This Python expression reads `<integer> <addition_operator> <integer>`.In Python, the addition operator (+) 
works by combining the expression on the left with the expression on the right in ordinary addition. In this case,
the result of the expression is `15`. 

We will see other examples of expressions that combine atoms in various ways as we go along.

### Assignment

The **assignment** is the Python statement that gives a value to a variable. It takes the following form:

```
<identifier> = <expression>
```

where `identifier` is the name of the variable and `expression` is its value. An example of this is

```python
pi = 3.14
```

The name of the variable `pi` is called the identifier. The value 3.14 is a floating point number, which is a literal.
What this does is associate the name `pi` with a storage location and place the value `3.14` in that location.

### Pass

The **pass** statement is an instruction that tells the computer to ignore this line and move on. Unlike a comment, the 
pass statement is read and understood by the computer as being told to move on. It is used as placeholders by 
programmers when they want to indicate that some functionality does not exist yet but will eventually.

### Delete

**Delete** is the removal of a variable from the program. It takes the form
```
del <identifier>
```

An example of this is
```python
del pi
```

After that statement is executed by the computer, there will no longer be a variable called pi.