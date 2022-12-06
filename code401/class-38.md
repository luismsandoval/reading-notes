# Asynchronous Actions

## async actions

1. Why use Redux middleware?

   - Helps you with logging, error reporting, making asynchronous requests.

2. Consider the Redux Async Data Flow Diagram. Describe the flow in your own words.

   - User clicks on action, dispatch sends action to middleware, middleware handle the response, middleware dispatches action upon completion of async call.

3. How are we accommodating async in our Redux app?

   - Using async to change the inventory available on the store front page.

## thunk middleware

1. Why would you need redux-thunk middleware?

   - Middleware extends the stores capabilities, allowing you to use async logic.

2. Redux Thunk middleware allows you to write action creators that return a \_\_\_\_ instead of an action.

   - _Function_

3. Describe how any return value from the inner thunk function will be made available.

   - It is the return value of the dispatch itself
