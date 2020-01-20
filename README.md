# Python Cheatsheet

This repository describes some of the tips and tricks for using the Python programming 
language.

## Running Python Scripts 

```bash
python <script name>
``` 

Replace "<script name>" with the file name of the Python script that you want to run.

## Declare Variables 

Variables hold the values that are used in your application or script. In Python, 
variables are not strong-typed. This means that the variables you declare,
are not limited to a particular data type. However, the variable does have a 
value, any future changes to that value must be of the same type. So you cannot set 
the value of a variable to a string and then change it to a integer. 

```python
myVariable = "red" 
myOtherVariable = false
myOtherOtherVariable = 5
``` 

## Functions

To write a function in Python, you start the function out with the "def" keyword. 

### Example

```python
def myFunction (param1, param2, param3): 
   sum = param1 + param2 + param3
   return sum
```

If you notice, there are no braces or brackets around the contents of the function. 
Python relies on indentation for the grouping of lines together within a given 
section.

## Random Number

Random nubmers can be used to do countdowns or other things that are needed. 
To get a random number, you have to import the randomint class from the random library 
by adding 

```
from random import randint
```

to the top of your Python script. 

Then you can set the random integer to a variable by doing 

```
myNumber = randint(5,60)
```

In the example above, 5 is the lower limit of the range and 60 is the upper limit
of the range. If your range needs to be different, then changes either or both of 
these values.

## More Resources

The Raspberry Pi traffic light project is written in Python code. You can review the 
code at 
[https://github.com/almostengr/raspitraffic-stem](https://github.com/almostengr/raspitraffic-stem).

