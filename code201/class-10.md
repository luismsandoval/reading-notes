# Class 10 3/15/2022

## Error Handling and Debugging

### The Stack

JavaScript processes only one line of code at a time. When data is needed from a seperate function, the new function will be *stacked* on top of the current stack. Hence, the Stack. The JS interpreter places the *current* statement on hold, then runs the code at the top of the stack, before moving on to the next statement.

### Error objects

When an error occurs, you can use your browser tools to find the error object. Error objects will give you a brief description of the error and where it is occuring. They will have the following properties:

- `name`: type of execution

- `message`: description

- `fileNumber`: name of JS file

- `lineNumber`: line where error occurs

Here are the 7 types of error objects in JS:

- `Error`: generic

- `SyntaxError`: syntax has not been followed

- `ReferenceError`: reference a variable that is not declared *or* not within scope

- `TypeError`: unexpected data type

- `RangeError`: numbers not in range

- `URIError`: `encodeURI()`, `decodeURI()`, et cetera not used correctly

- `EvalError`: `eval()` not used correctly

## ***USE THE CONSOLE LOG***

### Breakpoints

Using breakpoints we can pause the execution on any line.

### Try, Catch, Finally

If we know we may have an error, using try, catch, finally, we can still run the rest of the script even if an error occurs. A message will be shown on the console log to users regarding the error.
