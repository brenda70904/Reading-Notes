## [Your First Component](https://react.dev/learn/your-first-component)

### What are the building blocks of a React app?
Components, html, css , DOM 
### What is the difference between an element and a React component?
In React, elements and components are two separate concepts. Elements are plain JavaScript objects that describe a DOM element, a user-defined component, or static text. Components, on the other hand, are reusable functions or classes that return an element and encapsulate the logic for rendering a part of the UI.
### What are some advantages of React’s component based architecture?
It has reusable UI elements for your app, easy to  manage.


### [introducing JSX](https://legacy.reactjs.org/docs/introducing-jsx.html)

### What is JSX and why do we use it?
JSX is a syntax extension for JavaScript that allows you to write HTML-like code within your JavaScript files. We use JSX in React because it simplifies the process of creating and manipulating React elements, making the code easier to read and write.
### Describe the process of embedding JavaScript expressions in JSX.
In JSX, you can embed JavaScript expressions by enclosing them in curly braces {}. This allows you to dynamically render values from JavaScript variables or expressions within the HTML-like syntax of JSX.
### Is it safe to embed user input in JSX? Explain.
No, to prevent xss attack , Everything is converted to a string before being rendered. 


### [rendering elements](https://legacy.reactjs.org/docs/rendering-elements.html)

### Explain what a React Component is to a non-technical friend.
Imagine playing with a set of Legos where each piece is like a small machine. A React Component is like a Lego piece that has its own set of rules and behaviors, and you can snap together different pieces to create a big, awesome machine (or website!) that does cool things.
### Describe mutability and React Components, specifically, how is the UI updated?
Mutability refers to the ability of an object to be changed after it has been created. In React, components are designed to be immutable to ensure that the UI is updated in a consistent and predictable way. Instead of modifying existing components, React creates new virtual representations of the component and updates the UI by comparing the new version with the old version. This approach ensures that the UI is always up-to-date and avoids unexpected side effects that can arise from modifying components directly.
### If changes are made to the UI, what does React update?
If changes are made to the UI, React updates the virtual representation of the component that corresponds to those changes. It then compares this new version of the component to the previous version, calculates the differences between them, and updates only the parts of the UI that need to be changed.
