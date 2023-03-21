## [Thinking in React](https://react.dev/learn/thinking-in-react)

### Summarize the five steps of thinking in React.
1. Break the UI into a component hierarchy
- If you are working with the designer, they might have already named the components for you.
- Keep the single responsibility principle while designing the page structures
- Consider the styling tool and how I want to make a selector
2. Build a static version in React
- you identify the minimal set of UI state that your app needs and hard code it into your components. Then, you build a static version of your app that renders your data model, passing data down the component hierarchy as props.
3. Find the minimal but complete representation of the UI state
- You add stateful components and update the data flow as necessary to ensure that the UI state of your app is updated in response to user input.
4. Identify where your state should live
- you introduce two-way data binding by allowing child components to update the state of their parent components through callback functions. By passing down the functions as props, the child component can update the parent's state, which in turn, re-renders the entire application. This allows for a more interactive and responsive user experience.
5. Add inverse data flow
- Identify the minimal representation of UI state needed for rendering and move the state to the highest common ancestor component. You then pass the state down to the child components as props. This ensures that any changes in the state of the parent component are propagated to its child components through props, simplifying the data flow and minimizing the number of components that need to re-render.


## [State: A Component’s Memory](https://react.dev/learn/state-a-components-memory)

### What is one reason a local variable isn’t sufficient for managing a React component?
One reason a local variable isn't sufficient for managing a React component is that React components are designed to manage their state and render based on that state. A local variable can be mutated, but it won't trigger a re-render of the component, whereas updating the state will.

### What is the argument to the useState hook, and what are the two parts of its return array?
`[index, setIndex]`
### How can Component A access state from Component B?


