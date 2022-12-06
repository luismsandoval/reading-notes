# Application State with Redux

1. What is the first principle of Redux?

   - The state of the whole app is stored in an object tree within a single redux store.

2. what is a store and what do we use our reducers for within that store?

   - Holds the current app state. Reducer lets you dispatch actions.

3. Name three Redux store methods given to us by createStore and describe their use.

   - `getState()` -- returns current state
   - `dispatch()` -- dispatch actions to change state
   - `subscribe()`

4. Explain to a non-technical recruiter what `combineReducers()` does and why it is useful.

   - Turns an object whose values are different reducing functions into a single reducing function
