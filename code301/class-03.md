# Class 03

## Lists and Keys

1. What does .map() return?

   - Returns a new array.

2. If I want to loop through an array and display each value in JSX, how do I do that in React?

   - We can use curly braces to build elements. Return JSX elements with the curly brace.

   ```javascript
    const numbers = [1, 2, 3, 4, 5];
    const listItems = numbers.map((number) =>
    <li>{number}</li>
    );
    ```

    - Then include `listItems` inside a `<ul>`

3. Each list item needs a unique ____.

   - Key! I think? Like an ID attribute.

4. What is the purpose of a key?

   - Keys help React identify which items have been altered.

## The Spread Operator

1. What is the spread operator?

   - The syntax is an ellipsis of three dots `...` The operator "spreads" the array into seperate arguments.

2. List 4 things that the spread operator can do.

   1. Copy an array

   2. Using math functions

   3. Using an array as an argument

   4. Adding to state in react


3. Give an example of using the spread operator to combine two arrays.

   -

   ```javascript
     const hello = ['hello', 'world'];
     const greeting = ['how', 'are', 'ya'];

     const helloWorld = [...hello,...greeting];

     console.log(helloWorld);
   ```

4. Give an example of using the spread operator to add a new item to an array.

   -

   ```javascript
    const weekend = ['saturday', 'sunday'];
    const week = ['monday', 'tuesday', 'wednesday', 'thursday', 'friday', ...weekend]

    console.log(week);
   ```

5. Give an example of using the spread operator to combine two objects into one.

   -

   ```javascript
    const hello = {hello: 'hello'}
    const world = {world: 'world'};

    const helloWorld = {...hello,...world};

     console.log(helloWorld);
   ```

## How to Pass Functions between Components

1. In the video, what is the first step that the developer does to pass functions between components?

   - First we create the function wherever the state is that we are trying to change.

2. In your own words, what does the `increment` function do?

   - Increment is increasing at a fixed rate.

3. How can you pass a method from a parent component into a child component?

   - From my understanding, after you first create your method, you can create a new variable in the child element to hold the function, thus passing that method down.

4. How does the child component invoke a method that was passed to it from a parent component?

   - Since we now have access to the method, we can place `this.props.method` inside of the onClick handler. This calls the method from the parent component.

*:

- [List and Keys](https://reactjs.org/docs/lists-and-keys.html)

- [Spread Operator](https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab)

- [How to Pass Functions between Components](https://www.youtube.com/watch?v=c05OL7XbwXU&ab_channel=SteveGriffith-Prof3ssorSt3v3)
