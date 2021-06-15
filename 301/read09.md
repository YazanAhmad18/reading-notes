# What is functional programming?
## Functional programming is a programming paradigm — a style of building the structure and elements of computer programs 

# What is a pure function and how do we know if something is a pure function?
## A pure function is a function which:Given the same input, will always return the same output,Produces no side effects., Pure function should not rely on the external state

# What are the benefits of a pure function?
## They are easier to reason about ,easier to combine , easier to test ,easier to debug, easier to parallelize

# What is immutability?
## its state cannot change after it’s created. If you want to change an immutable object, you can’t

# What is Referential transparency?
## Basically, if a function consistently yields the same result for the same input, it is referentially transparent.
## pure functions + immutable data = referential transparency

# What is a module? 
## A module is a part of a code that represent some functionality, and is made to be used in other code. So instead of writing a big code in one file, we split the code into pieces of modules. 

# What does the word  require do?
## require will import the module, and enable us to use its functionality.

# How do we bring another module into the file the we are working in?
## Call module const counter = require('\path')

# What do we have to do to make a module available?
## export the part of module we want it to be available to other files like module.export counter


