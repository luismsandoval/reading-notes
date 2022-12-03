# Context API

## Hooks and Context

1. With regard to the React Context API, what does a “provider” do?

   - Allows components to subscribe to context changes.

2. With regard to the React Context API, how would we implement a “consumer” role?

   - use createContext, use the context to wrap the provider around your components. Put a value in the context props and read that value within your components using context consumer.

3. Specifically with Context, how are we “wrapping” components to achieve our goals?

   - Wrap at the top level/root

## Awesome React Context links

1. Consume content from (at least) two more of the Awesome React Context links. After some familiarity with React Context, once again share your takeaways from each:
   1. Takeaway 1: Very easy to change themes across the whole app with context.
   2. Takeaway 2: useContext re-renders everything, not always what we want. Use sparingly.
