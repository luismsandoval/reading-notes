# Component Lifecycle / `useEffect` Hook

## effects hook

1. What purpose does useEffect serve in a function component compared to its counterpart(s) in class components?

   - useEffect hook is componentDidMount, componentDidUpdate, and componentWillUnmount combined.

2. When using the useEffect Hook:

   1. What does useEffect do?

      - It tells React that your component needs to do something after render. React remembers the function passed, and later calls it after performing DOM updates.

   2. Why is useEffect called inside a component?

      - This allows us access to any state variable or props.

   3. Does useEffect run after every render?

      - Yes, by default. However you can pass it an array as a second argument, and if what is included in that array does not change, React will skip applying an effect.

3. Explain the importance of properly implementing effects with Cleanup

   - The cleanup function prevents memory leaks helps prevent bugs.
