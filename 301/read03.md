## i understand the concept of map function in react we use it to return new array and inside it list of items that we need no matter data type of the items

## What does .map() return?
### it is return new array 

## If I want to loop through an array and display each value in JSX, how do I do that in React?
### we use map function to loop though elements 

## Each list item needs a unique?
### key 

## What is the purpose of a key?
### Keys help React identify which items have changed, are added, or are removed in this way no need to retrieve data we do not  need this is will be good to save time 

## What is the spread operator?
### the spread operator in javascript syntax is short and quick combining arrays or objects, and spreading an array out into a function’s arguments we use for it use of an ellipsis of three dots

## List 4 things that the spread operator can do?
* Copying an array
* Concatenating or combining arrays
* Using Math functions
* Using an array as arguments

## Give an example of using the spread operator to combine two arrays.?
` const myArray = [`🤪`,`🐻`,`🎌`]
const yourArray = [`🙂`,`🤗`,`🤩`]
const ourArray = [...myArray,...yourArray]
console.log(...ourArray) // 🤪 🐻 🎌 🙂 🤗 🤩`



## Give an example of using the spread operator to add a new item to an array?
` const fewFruit = ['🍏','🍊','🍌']
const fewMoreFruit = ['🍉', '🍍', ...fewFruit]`

## Give an example of using the spread operator to combine two objects into one?

`const objectOne = {hello: "🤪"}
const objectTwo = {world: "🐻"}
const objectThree = {...objectOne, ...objectTwo, laugh: "😂"}`

## what is the first step that the developer does to pass functions between components?
### bulding the objects inside the constructor

## In your own words, what does the increment function do? when click the button the  state will be shown that ### is update it and increase the count one every time

## How can you pass a method from a parent component into a child component?
### we can do this using the props to move the properties and its value from one component to other 

## How does the child component invoke a method that was passed to it from a parent component?
### as i understand from this question is how we connect the child with parent through extend word  then import child page to parent page to send the methods propties what ever