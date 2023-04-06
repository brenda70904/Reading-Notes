[Redux Toolkit (RTK)](https://redux-toolkit.js.org/introduction/getting-started)

### What concerns are addressed by Redux Toolkit?
- Configuring a Redux store is too complicated
- has to install lots of package 
- Redux requires too much boilerplate code

### What does `configureStore()` do?
wraps `createStore()` to provide simplified configuration options and good defaults. It can automatically combine your slice reducers, adds whatever Redux middleware you supply, includes redux-thunk by default, and enables use of the Redux DevTools Extension.

### How would I use `createSlice()`?
it accepts an object of reducer functions, a slice name, and an initial state value, and automatically generates a slice reducer with corresponding action creators and action types.

[MobX](https://mobx.js.org/getting-started.html)

### What is Mobx?
MobX is a state management library for JavaScript applications that provides observable data structures, reactive functions, and computed values to simplify the process of managing the application's state.

### How does MobX make it “impossible” to produce an inconsistent state?
MobX ensures that the state of a JavaScript application remains consistent by providing a mechanism to track changes to observable data structures, and automatically updating any parts of the application that depend on those changes. By using observables and actions to manage the state, MobX makes it easy to keep the state of the application in sync with the data, preventing inconsistencies from occurring. Additionally, MobX uses a reactive programming model that ensures that any updates to the state are applied consistently throughout the application, making it virtually impossible to produce an inconsistent state.

### How would we build a reactive user interface?
To build a reactive user interface, we can use a state management library like MobX to track changes to the state of the application, and use reactive programming techniques to automatically update the user interface in response to those changes. By using this approach, the user interface will always reflect the current state of the application, making it responsive and intuitive for the user.
