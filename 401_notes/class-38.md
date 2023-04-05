# [async actions](https://redux.js.org/tutorials/fundamentals/part-6-async-logic)

### Why use Redux middleware?
- Handling asynchronous logic
- Logging
- Caching
- Analytics
### Consider the Redux Async Data Flow Diagram. Describe the flow in your own words.
1. The user triggers an action that initiates an asynchronous operation, such as fetching data from an API.
2. The action is dispatched to the Redux store, which updates the state and triggers a re-rendering of the UI.
3. The action is intercepted by a middleware, such as Redux-Thunk, which checks if the action is a function. If it is a function, the middleware calls it with the dispatch and getState methods as arguments.
4. The function (also known as an async action creator) initiates the asynchronous operation, such as an API call, and dispatches additional actions to update the store with the results of the operation.
5. While waiting for the asynchronous operation to complete, the middleware may dispatch additional actions to update the state of the application, such as setting a loading flag to true.
6. Once the asynchronous operation is complete, the async action creator dispatches a final action to update the store with the results of the operation, such as the fetched data.
7. The store updates its state with the new data and triggers a re-rendering of the UI.
8. The UI displays the new data to the user, completing the flow of data.
<!-- Once upon a time, in the land of Redux, there was a brave hero named "User". User had a great quest to fetch some data from an API.

User knew that fetching data is a dangerous task, as it involves waiting for a long time and facing many errors along the way. So, User decided to seek the help of a wise wizard called "Async Action Creator".

The wizard knew all about the art of handling async data, and gave User a magical incantation called "fetchData". User used this incantation to send a request to the API, and waited patiently for the response.

Meanwhile, the Redux store was on standby, waiting for User to dispatch the action. When the response arrived, User dispatched an action with the fetched data. The action traveled through the middleware, where it was intercepted by another wizard called "Thunk".

Thunk knew how to handle functions as actions, and used its powers to call the magical incantation "dispatch". The incantation dispatched the action to the reducers, where the data was merged into the store.

The store was now updated with the new data, and User was finally able to complete their quest. User was very grateful to the wise wizard, and continued on their journey through the land of Redux, with confidence in their heart and data in their store. The end. -->

### How are we accommodating async in our Redux app?
In Redux, we typically use middleware, such as Redux-Thunk or Redux-Saga, to accommodate asynchronous operations. These middleware intercept actions before they reach the reducers, allowing us to perform asynchronous operations and dispatch additional actions as necessary.

# [thunk middleware](https://github.com/reduxjs/redux-thunk)

### Why would you need redux-thunk middleware?
You would need Redux-Thunk middleware in your Redux application if you need to handle asynchronous operations, such as making API calls or waiting for a response from a server, before dispatching an action to update the Redux store.
### Redux Thunk middleware allows you to write action creators that return a ____ instead of an action.
**function**
### Describe how any return value from the inner thunk function will be made available.
Any return value from the inner thunk function will be made available as the return value of the dispatch function that invoked the async action creator.



