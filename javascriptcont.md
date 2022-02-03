# JavaScript Continued

## Functions

A JS function is a block of code that's purpose is to perform a specific task. This function is executed when it is invoked. 

```
function myFunction(p1, p2) {
  return p1 * p2;   // The function returns the product of p1 and p2
}
```

### Syntax

Defined with `function` followed by a **name** followed by **()**.

Function names follow the same rules as variables.

The **()** can include parameters seperated by commas: **(p1, p1)**

Note: Think of parameters as local variables

The code that is executed lives inside the **{}**

```
function name(parameter1, parameter2, parameter3) {
  // code to be executed
}
```

### Invocation

The code inside the function will run when something invokes or *calls* the function.

- When an event occurs (user clicks a button)

- When it is called from JS code

- Auto (self invoked)

### Return

When the code reaches `return` the function will stop running. 

If a return value is computed, the return valued is then *returned* back to the *caller*.

```
let x = myFunction(4, 3);   // Function is called, return value will end up in x

function myFunction(a, b) {
  return a * b;             // Function returns the product of a and b
}
```

## Operators

### Arithmetic Operators

- \+ Addition

- \- Substraction

- \* Multiplication

- \** Exponentation 

- / Division

- % Modulus (division remainder)

- \++ Increment

- \-- Decrement

### Assignment Operators

- = 

- \+=

- \-=

- \*=

- /=

- %=

- \**

### String Operators

The `+` and `+=` operator can be used to add strings.

```
let text1 = "John";
let text2 = "Doe";
let text3 = text1 + " " + text2;
```
```
let text1 = "What a very ";
text1 += "nice day";
```

### Comparison Operators

- == equal to

- === equal value and type

- != not equal

- \> greater than

- \< less than

- \>= greater than or equal to

- \< less than or equal to

- ? ternary operator

## Logical Operators

- && logical and

- || logical or

- ! logical not

## Type Operators

- typeof Returns the type of variable

- instanceof Returns true if an object is an instance of an object type

[Back](javascript.md) [Next](operators-and-loops.md)