# In Tests We Trust — TDD with Python
## TDD stands for Test-Driven Development. Unit tests are some pieces of code to exercise the input, the output and the behaviour of your code. You can write them anytime you want. The test file name should follow the same name of module name. For instance, if our module is gender.py, our test name should be test_gender.py. It’s ideal to separate the tests folder from production code (the implementation).

# Baby Steps:

## The API is pretty straightforward and your work was almost done. But with TDD we need to think about tests first. And to be ok with the possibility of the beginning to be hard sometimes — and it’s totally fine.

* AAA: Arrange, Act and Assert.
* Arrange: you need to organize the data needed to execute that piece of code (input);
* Act: here you will execute the code being tested (exercise the behaviour);
* Assert: after executing the code, you will check if the result (output) is the same as you were expecting.

## The Cycle:
* 🆘 Write a unit test and make it fail (it needs to fail because the feature isn’t there, right? If this test passes, call the Ghostbusters, really)
* ✅ Write the feature and make the test pass! (you can dance after that)
* 🔵 Refactor the code — the first version doesn’t need to be the beautiful one (don’t be shy)


# Recursion:
## The process in which a function calls itself directly or indirectly is called recursion and the corresponding function is called as recursive function. In the recursive program, the solution to the base case is provided and the solution of the bigger problem is expressed in terms of smaller problems. The idea is to represent a problem in terms of one or more smaller problems, and add one or more base conditions that stop the recursion

## How a particular problem is solved using recursion?
### The idea is to represent a problem in terms of one or more smaller problems, and add one or more base conditions that stop the recursion.

## Why Stack Overflow error occurs in recursion?

### If the base case is not reached or not defined, then the stack overflow problem may arise. Let us take an example to understand this.

## What is base condition in recursion?

### In the recursive program, the solution to the base case is provided and the solution of the bigger problem is expressed in terms of smaller problems.

# What does the if __name__ == “__main__”: do?

## Advantages : 

* Every Python module has it’s __name__ defined and if this is ‘__main__’, it implies that the module is being run standalone by the * * user and we can do corresponding appropriate actions.
* If you import this script as a module in another script, the __name__ is set to the name of the script/module.
* Python files can act as either reusable modules, or as standalone programs.
* if __name__ == “main”: is used to execute some code only if the file was run directly, and not imported.


## Python Strings
### Python has a built-in string class named "str" with many handy features (there is an older module named "string" which you should not use). String literals can be enclosed by either double or single quotes, although single quotes are more commonly used. Backslash escapes work the usual way within both single and double quoted literals -- e.g. \n ' ". A double quoted string literal can contain single quotes without any fuss (e.g. "I didn't do it") and likewise single quoted string can contain double quotes. A string literal can span multiple lines, but there must be a backslash \ at the end of each line to escape the newline. String literals inside triple quotes, """ or ''', can span multiple lines of text.


## String Methods:
* s.lower(), s.upper() -- returns the lowercase or uppercase version of the string
* s.strip() -- returns a string with whitespace removed from the start and end
* s.isalpha()/s.isdigit()/s.isspace()... -- tests if all the string chars are in the various character classes
* s.startswith('other'), s.endswith('other') -- tests if the string starts or ends with the given other string
* s.find('other') -- searches for the given other string (not a regular expression) within s, and returns the first index where it begins or -1 if not found
* s.replace('old', 'new') -- returns a string where all occurrences of 'old' have been replaced by 'new'
* s.split('delim') -- returns a list of substrings separated by the given delimiter. The delimiter is not a regular expression, it's just text. 'aaa,bbb,ccc'.split(',') -> ['aaa', 'bbb', 'ccc']. As a convenient special case s.split() (with no arguments) splits on all whitespace chars.
* s.join(list) -- opposite of split(), joins the elements in the given list together using the string as the delimiter. e.g. '---'.join(['aaa', 'bbb', 'ccc']) -> aaa---bbb---ccc