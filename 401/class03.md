## 1. Files in Python:Files on most modern file systems are composed of three main parts:

  * Header: metadata about the contents of the file (file name, size, type, and so on).
  * Data: contents of the file as written by the creator or editor.
  * End of file (EOF): special character that indicates the end of the file.
   
#  What this data represents depends on the _format specification_ used, which is typically represented by an extension.
 
##   When you access a file on an operating system, a file path is required. The file path is a string that represents the location of a file. It’s broken up into three major parts:

  * Folder Path: the file folder location on the file system where subsequent folders are separated by a forward slash `/` (Unix) or backslash `\` (Windows).
  * File Name: the actual name of the file.
  * Extension: the end of the file path pre-pended with a period (.) used to indicate the file type.


### Problems with files:
  * The representation of a new line or line ending.
  *  the encoding of the byte data. An encoding is a translation from byte data to human readable characters.
      This is typically done by assigning a numerical value to represent a character. The two most common encodings are the `ASCII` and `UNICODE` Formats.

## Opening and closing a file in Python:
When you want to work with a file, the first thing to do is to open it. This is done by invoking the `open()` built-in function. 
`open()` has a single required argument that is the path to the file. `open()` has a single return, the file object (Text files, Buffered binary files, Raw binary files).

When you want to work with a file, the first thing to do is to open it. This is done by invoking the open() built-in function. open() has a single required argument that is the path to the file. open() has a single return, the file object. ​you may want to append to a file or start writing at the end of an already populated file. This is easily done by using the 'a' character for the mode argument


## 2. Exceptions in Python:
Syntax errors occur when the parser detects an incorrect statement. Observe the following example:
```
>>> print( 0 / 0 ))
  File "<stdin>", line 1
    print( 0 / 0 ))
                  ^
SyntaxError: invalid syntax
```
The arrow indicates where the parser ran into the syntax error. In this example, there was one bracket too many. 
We can use `raise` to throw an exception if a condition occurs. The statement can be complemented with a custom exception.
If you want to `throw` an error when a certain condition occurs using raise, you could go about it like this:
```
x = 10
if x > 5:
    raise Exception('x should not exceed 5. The value of x was: {}'.format(x))
 ```
 
##### The AssertionError Exception:
Instead of waiting for a program to crash midway, you can also start by making an assertion in Python. We `assert` that a certain condition is met. If this condition turns out to be `True`, then that is excellent! The program can continue. If the condition turns out to be `False`, you can have the program `throw` an `AssertionError` exception.


## The try and except Block: Handling Exceptions:
### The try and except block in Python is used to catch and handle exceptions. Python executes code following the try statement as a “normal” part of the program. The code that follows the except statement is the program’s response to any exceptions in the preceding try clause.


## The else Clause
### In Python, using the else statement, you can instruct a program to execute a certain block of code only in the absence of exceptions.
 
## The try and except Block: Handling Exceptions
### The try and except block in Python is used to catch and handle exceptions. Python executes code following the try statement as a “normal” part of the program. The code that follows the except statement is the program’s response to any exceptions in the preceding try clause