[Extracting State Logic into a Reducer](https://react.dev/learn/extracting-state-logic-into-a-reducer)

### What is the motivation for adding a reducer?
using useReducer can help us manage complex state changes in a more scalable and predictable way, making it easier to maintain and debug our codebase.
### What are actions in the context of a reducer? How are they different than setting state directly?
In the context of useReducer in React, actions are similar to those in Redux. They are plain JavaScript objects that describe a change to be made to the state of a component. An action typically includes a type field that indicates the type of change to be made and may also include additional data or payload that provides context or information needed to perform the change.
The useReducer hook takes a reducer function and an initial state value and returns a state object and a dispatch function. The dispatch function is used to dispatch actions to the reducer, which then returns a new state object based on the action and the current state.

### What common list operation is useReduce named for, and why?
`reduce`
### When should you switch from useState to useReducer?
When you have a bug with useState, it can be difficult to tell where the state was set incorrectly, and why. 


