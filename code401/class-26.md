# Component Based UI

## react hello world

1. What are the building blocks of a React app?

   - _Elements_ and _Components_

2. What is the difference between an element and a React component?

   - An element describes what you want to see on the screen. Components are made up of elements. Components are independent, reusable pieces of UI.

3. What are some advantages of React’s component based architecture?

   - The components are independent and reusable.

## introducing JSX

1. What is JSX and why do we use it?

   - A syntax extension to JS. Used with React to describe what the UI should look like.

2. Describe the process of embedding JavaScript expressions in JSX.

   - You place any valid JS expression inside curly brackets. i.e. `<h1> Hello {name} </h1>`

3. Is it safe to embed user input in JSX? Explain.

   - Yes! React DOM _escapes_ any values embedded in JSX before rendering them. You can never inject something that is not explicitly written in your app.

## rendering elements

1. Explain what a React Component is to a non-technical friend.

   - A component is a collection of elements that make up a piece of UI.

2. Describe mutability and React Components, specifically, how is the UI updated?

   - React elements are immutable. The only way to update the UI is to rerender the component.

3. If changes are made to the UI, what does React update?

   - Only the node whose contents have changed get updated by React DOM.

### sources

- [react hello world](https://reactjs.org/docs/hello-world.html)
- [introducing JSX](https://reactjs.org/docs/introducing-jsx.html)
- [rendering elements](https://reactjs.org/docs/rendering-elements.html)
