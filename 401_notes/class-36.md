# [Dan Abramov Redux Tutorials](https://egghead.io/courses/fundamentals-of-redux-course-from-dan-abramov-bd5cc867)

### What is the first principle of Redux?
All of the state will be present as a single JS object
### what is a store and what do we use our reducers for within that store?
a store is a JavaScript object that holds the state of your application. The store is the single source of truth for your application's state, and it is where you keep all the data that your application needs to function.Reducers are typically used within the store to update the state in response to user interactions or other events that occur within your application.
### Name three Redux store methods given to us by createStore and describe their use.
`getState()`: This method returns the current state of the store. You can use it to retrieve the current state at any time, or to log or debug the state of your application.

`dispatch(action)`: This method is used to update the state of the store. You pass an action object to dispatch, and the store uses a reducer function to update the state based on the action. The new state is then returned by the reducer, and becomes the new state of the store. You can use dispatch to trigger updates to your application's state in response to user interactions, API responses, or other events.

`subscribe(listener)`: This method allows you to register a listener function that will be called every time the state of the store changes. The listener function is passed the current state of the store as an argument, and can be used to update the user interface or perform other actions in response to changes in the application state. You can use subscribe to ensure that your application's UI is always up-to-date with the current state of the store.


### Explain to a non-technical recruiter what combineReducers() does and why it is useful.
`combineReducers()` is a function in Redux that is used to combine multiple reducer functions into a single reducer function. This is useful in large-scale Redux applications where you might have multiple pieces of state that are managed by different reducers. By using combineReducers(), you can create a single reducer function that manages all of the state in your application. This simplifies your code and makes it easier to manage the state of your application.
