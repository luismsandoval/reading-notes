# Redux - Additional Topics

## Redux Toolkit (RTK)

1. What concerns are addressed by Redux Toolkit?

   - There is too much setup with the redux store. Too much boilerplate.

2. What does configureStore() do?

   - wraps `createStore` to provide simplified configuration options and good defaults

3. How would I use createSlice()?

   - `createSlice` takes a object of reducers, a slice name, and an initial state value.

## MobX

1. What is MobC?

   - a simple, scalable and battle tested state management solution.

2. How does MobX make it “impossible” to produce an inconsistent state?

   - Makes sure that everything that can be derived from the application state, will be derived. Automatically.

3. How would we build a reactive user interface?

   - The `observer` HoC wrapper from the mobx-react-lite package by wrapping the React component in autorun.
