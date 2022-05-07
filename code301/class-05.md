# Class 05

## Thinking in React

1. What is the single responsibility principle and how does it apply to components?

   - The idea that a component should only do one thing. If it ends up growing, it should be made into sub-components.

2. What does it mean to build a ‘static’ version of your application?

   - An application that renders but does not use state to alter data.

3. Once you have a static application, what do you need to add?

   - Your data model to the highest component.

4. What are the three questions you can ask to determine if something is state?

   1. Is it passed in from a parent via props? If so, it probably isn’t state.

   2. Does it remain unchanged over time? If so, it probably isn’t state.

   3. Can you compute it based on any other state or props in your component? If so, it isn’t state.

5. How can you identify where state needs to live?

   - State must be in a common owner component or another component higher up than all of the components in which it needs state to render.

## Higher-Order Functions

1. What is a “higher-order function”?

2. Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?

3. Explain how either map or reduce operates, with regards to higher-order functions.
