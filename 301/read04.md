# React Docs - Forms

## 1_What is a ‘Controlled Component’?
 * it depends on the user input and it keeps state as it is but when we want to update its the state we use the method set state,that takes its current value through props and notifies changes through callbacks like onChange

## 2_Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.
* We update the state with their responses as soon as they enter them, because when the user submits we will need to take the state value .

## 3_How do we target what the user is entering if we have an event handler on an input field?
* through using the value of each attribute ,the attributes have value in their state so in event.target.value we targeted on the value

# The Conditional (Ternary) Operator Explained:

## 1_Why would we use a ternary operator?
* Use the ternary operator to simplify your if-else statements that are used to assign values to variables
## 2-Rewrite the following statement using a ternary statement:
* x === y ? console.log(true) : console.log(false);