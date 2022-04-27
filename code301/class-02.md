# Class 02

## React Lifecycle

1. Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?

   - render

2. What is the very first thing to happen in the lifecycle of React?

   - During the mounting phase, the constructor of a component is called.

3. Put the following things in the order that they happen: `componentDidMount`, `render`, `constructor`, `componentWillUnmount`, `React Updates`

   1. `constructor`

   2. `render`

   3. `React Updates`

   4. `componentDidMount`

   5. `componentWillUnmount`

4. What does `componentDidMount` do?

   - A hook that is invoked right after a React component has been mounted. To my understanding, it is only invoked after the first lifecycle.

## React State vs Props

1. What types of things can you pass in the props?

   - Any data types can be passed from one component to another through props.

2. What is the big difference between props and state?

   - State is handled inside of the component while props are handled outside of the component.

3. When do we re-render our application?

   - When you change a state, it re-renders that section of the application.

4. What are some examples of things that we could store in state?

   - State can store user inputs for something like a form, and use that to update the application.
