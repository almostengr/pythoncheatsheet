# Python Cheatsheet

This repository describes some of the tips and tricks for using the Python programming 
language.

## Running Python Scripts 

```bash
python <script name>
``` 

Replace "<script name>" with the file name of the Python script that you want to run.

## Functions

To write a function in Python, you start the function out with the "def" keyword. 

### Example

```python
def myFunction (param1, param2, param3): 
   sum = param1 + param2 + param3
   return sum
```

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

