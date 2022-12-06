# Combined Reducers

## Multiple Reducers Example

1. Why create multiple reducers?

   - Easier to maintain.

2. How would you combine multiple reducers?

   - `combineReducers()`

3. How will you manage state as an immutable object? why?

   - `...state`

## Redux Docs: Using Combined Reducers

1. combineReducers is a utility function to simplify the most common use case when writing **\_ \_\_\_** .

   - _Redux reducers_

2. Explain how combineReducers assembles the new state tree.

   - `combineReducers` will call each slice reducer with its current slice of state and the current action, giving the slice reducer a chance to respond and update its slice of state if needed

3. How would you define initial state in an app using combineReducers?

   - `createStore` can take a preloadedState as a second argument. Or, the root reducer returns the initial store value when the state arg is `undefined`

## Redux Docs: Combined Reducer Syntax

1. Why will you want to split your reducing functions as your app becomes more complex?

   - Simpler to manage independent parts of state.

2. The **\_** helper function turns an object whose values are different reducing functions into a single reducing function you can pass to \_\_\_\_.

   - _`combineReducers`_ ... _`createStore`_

3. What is a popular convention when naming reducers?

   - Naming the reducers after the slices they manage.
