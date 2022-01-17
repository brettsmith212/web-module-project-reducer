# Understanding Questions:

1. What are the steps of execution from the pressing of the 1 button to the rendering of our updated value? List what part of the code excutes for each step.

- The user presses the 1 button.
- The the click of the button is handled with handleAddOne()
- addOne() in actions index.js is called and returns type: ADD_ONE to Dispatch()
- Dispatch() is called with value type: ADD_ONE, it enters the reducer() searching for the case: ADD_ONE
- After it finds it it returns the new state
- The component rerenders and displays plus 1

- TotalDisplay shows the total plus 1.
