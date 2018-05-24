##Variables  
A **variable** is a name that refers to a certain value.
In the example below you can see that when you enter ```x = 5``` that value (5) is stored into the variable x.  
When you input the command ```print x``` you will get 5


    >>> x = 5
    >>> print x
    5

Note: you can change the value of a variable after you create it:

```
>>> x = 5
>>> x = 6
>>> print x
6
```
The value of 5 will be stored in variable x until ````x=6``` _overwrites_ the first value making x equal to 6  

___
Variables can refer to different kinds of values:

```
>>> name = "Kyle"
>>> print name
Kyle
>>> pi = 3.14159
>>> print pi
3.14159
```
You can even assign a variable to be equal to the result of an arithmetic expression!

```
>>> my_num = 5 * (3 + 2)
>>> print my_num
25
```
...Or use them in arithmetic expressions:

```
>>> n = 5
>>> print 5 * n
25
```

---
###Making Your Programs Interactive  
  
So far, your programs have not been able to take any input from the user. However, getting parameters from the user and operating on them is a key part of programming.  
  
####Getting Input from the User  
  
To get text input from the user, use the ```raw_input()``` function.  
The example below takes the input and stores it in the variable name:  

```name = raw_input()```  

You can also put some text between the parentheses of the function for a prompt to ask the user:    
```name = raw_input(“What is your name?”)```  
  
_Example:_ 
 
    >>> name = raw_input()
The program will pause here to allow you to type in a value.

    Kyle     
This is something that the user types in

    >>> print name
    Kyle
    >>> x = raw_input(“Enter a number:”)
    Enter a number: 5 
 Be careful — x will be a string!
 
    >>> print x * 3
    555
    >>> print int(x) * 3
    15
  
 That's it! You just learned the fundamentals of **variables**. You may now celebrate... Or take the [quiz] first.
 
[quiz]: (https://nathansolomon1678.github.io/programmer-training/general/quizzes/variables)