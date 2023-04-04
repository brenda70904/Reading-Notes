## [Multiple Reducers Example](https://www.youtube.com/watch?v=gBER4Or86hE)

### Why create multiple reducers?
to manage the the state, in the real world there are multipe state and use reducer helps manages the state.
### How would you combine multiple reducers?
use `combineReducers`
### How will you manage state as an immutable object? why?

## [Redux Docs: Using Combined Reducers](https://redux.js.org/usage/structuring-reducers/using-combinereducers/)

### combineReducers is a utility function to simplify the most common use case when writing ___ _____ .
 redux reducers
### Explain how combineReducers assembles the new state tree.
When combineReducers is used to create the root reducer for a Redux application, it returns a function that takes the current state of the application and an action, and returns the new state of the application.
The new state tree is assembled by calling each individual reducer with the relevant slice of the state tree and the action, and combining the results into a new state tree.

### How would you define initial state in an app using combineReducers
To define the initial state in an app that uses combineReducers, you can create an object that has the same keys as the individual reducers, with each key representing the initial state for that particular reducer.


##[Redux Docs: Combined Reducer Syntax](https://redux.js.org/api/combinereducers/)

### Why will you want to split your reducing functions as your app becomes more complex?
As an app becomes more complex, the amount of state managed by the application increases. It can be difficult to manage the state of the entire application using a single reducer function. Splitting the reducer function into multiple smaller reducers can make it easier to manage and reason about the state of the application.

### The _____ helper function turns an object whose values are different reducing functions into a single reducing function you can pass to ____.
`combineReducers`
### What is a popular convention when naming reducers
use the name of the state slice they manage as the name of the reducer
