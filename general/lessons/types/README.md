# Types

##### We’ve seen that variables can refer to different kinds of data:

* Integer numbers: 0, 1, -3
* Decimal numbers: 0.0, 1.0, 3.1415
* Text: “Hello, world!”

### The different types in python are:

### str

str stands for string, which is just some text, and is written by surrounding text with quotation marks (“”). Other examples of string values:

* “Siddarth”
* “3”
* “some other random text”

### int

int stands for Integer and represents any real whole number. Other examples of int values include:
* 1
* 4*2
* 100000

### float
A float is just some number but not necessarily a whole number. It is basically a number with decimal places or just any real number. Examples of float values include:
* 2 + 0.7
* 3.1415
* 3.0

Although 3.0 can be represented as a whole number, the decimal point makes it into a float, not an int.

## Converting Between Types
* What if you have a float value (5.0) and you want to turn it into an integer?
* What if you want to get an integer from a string?

Casting can change a variable between types!

```
>>> int(“5”)
5
>>> float(“3.5”)
3.5
>>> str(5.2)
‘5.2’
```

## Converting Values That Don't Make Sense
###### What if a cast doesn’t make complete sense?
* Converting a non-whole number into an integer will just round down (4.0 → 4, 4.5 →4, 4.9 → 4, 5.0 → 5)
* Converting between things that make no sense whatsoever (like trying to get a float out of a string that doesn’t have a number in it) will cause an error.

```
>>> int(5.3)
5
>>> float(“hello!”)
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
ValueError: could not convert string to float: hello!
```

### Side Note: Integer Division
Remember this?

```
>>> 5 / 2
2
```

Well, it turns out that Python only rounds down division when it detects that both of the operands (5 and 2 in this case) are integers! To force it to do real division, you can cast one to a float:

```
>>> float(5) / 2.
2.5
```

## Try it out!
###### Try to these these simple challanges to familarize yourself with python types.
* Create a variable of each type that we’ve gone over so far: strings, ints, and floats
* Try adding together and subtracting the variables you made
* What happens if you try to multiply a string by an integer? What if you multiply it by a float?
* What if you try to add two strings together?
