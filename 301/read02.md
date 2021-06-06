# React lifecycle :
 ## Based on the diagram, what happens first, the ‘render’ or the ‘componentDidMount’? depends on the diagram  render is going to be first 

 ## What is the very first thing to happen in the lifecycle of React? Mounting (constructor) the most important thing is to build it

## Put the following things in the order that they happen?
### 1)constructor ,2)render ,3)React Updates ,4)componentDidMount ,5)componentWillUnmount .

## What does componentDidMount do?
### componentDidMount: this happen after building the constructor f you need to load anything using a network request or initialize the DOM


## React State Vs Props :
 ### What types of things can you pass in the props? pass variables from one to another component of the tree components

### What is the big difference between props and state?
### Basically, the difference is that state is something like attributes in OOP: it's something local to a class (component), used to better describe it. Props are like parameters - they are passed to a component from the caller of a component (the parent) : as if you called a function with certain parameters.

### When do we re-render our application?
### automatically re-render whenever there is a change in their state or props. A simple update of the state, from anywhere in the code

### What are some examples of things that we could store in the state? state, store, static