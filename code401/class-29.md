# Advanced State with Reducers

## `useReducer` hook

1. Name an alternative to the useState Hook.

   - `useReducer`

2. Why might the useReducer Hook be preferable to the useState Hook?

   - "when you have complex state logic that involves multiple sub-values" or when the next state is dependent on the current state.

3. What are two ways to set the initial state?

   - Pass the initial state as a second argument, pass an `init` function as the third argument.

## Ultimate Guide to `useReducer`

1. In terms of state, what does useReducer expect to receive as a parameter?

   - A reducer function and the initial state.

2. What does useReducer return?

   - An array with the current state value and a `dispatch` function that can be passed as an action.

3. Explain dispatch to a non-technical recruiter.

   - The dispatch function sends the type of action to the reducer function (updating the state).

### Sources

- [`useReducer` hook](https://reactjs.org/docs/hooks-reference.html#usereducer)

- [Ultimate Guide to `useReducer`](https://blog.logrocket.com/react-usereducer-hook-ultimate-guide/)
