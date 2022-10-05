# Introducing Hooks

1. What was the motivation for introducing Hooks?

   - Hooks allow the reuse of stateful logic without changing the hierarchy of components.

   - Hooks let you split a component into smaller functions based on what's related.

   - Hooks let you use more React features without classes.

2. What changes are important regarding implementing Hooks versus Component Classes?

   -

3. Hooks allow you to reuse stateful logic without changing **\_\_\_**.

   - component hierarchy

# hooks api

1. Name two rules imposed by React Hook usage.

   - Only call Hooks **at the top level**. Not inside loops, conditions, nested functions.

   - Only call Hooks **from React function components**. Do not call Hooks from regular JS functions.

2. How would you identify a custom Hook and why might you create one?

   - When you want to reuse _stateful logic_, not state. You can create a custom hook to use on different components, and the state remains completely independent. The function name starts with "use" and calls other Hooks.

# the state hook

1. What is a Hook?

   - Hooks let you use state and other React features without a Class.

2. When would I use the useState Hook?

   - Whenever you want to declare a new state variable.

3. If you were to add React state to a function component by declaring a state variable:

   1. What does calling useState do?

      - useState declares a new state variable.

   2. What do we pass to useState as an argument?

      - The initial value of the state variable.

   3. What does useState return?

      - the current state and the function that updates it. i.e `[count, setCount]=useState(0)`
