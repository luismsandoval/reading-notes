# Operators and Loops

## Assignment Operators

This operator assigns a value.

- = 

- \+=

- \-=

- \*=

- /=

- %=

- \**

### Assigning properties

```
let obj = {};

obj.x = 3;
console.log(obj.x); // Prints 3.
console.log(obj); // Prints { x: 3 }.

const key = "y";
obj[key] = 5;
console.log(obj[key]); // Prints 5.
console.log(obj); // Prints { x: 3, y: 5 }.
```

### Destructuring

```
var foo = ['one', 'two', 'three'];

// without destructuring
var one   = foo[0];
var two   = foo[1];
var three = foo[2];

// with destructuring
var [one, two, three] = foo;
```

### Evaluation and nesting

```
// Declares a variable x and initializes it to the result of f().
// The result of the x = f() assignment expression is discarded.
let x = f();

// Declares a variable x and initializes it to the result of g().
// The result of the x = g() assignment expression is discarded.
x = g(); // Reassigns the variable x to the result of g().
```

## Comparison Operators

This operator compares its operands and returns a logical value based on whether or not it is true.

- == equal to

- === equal value and type

- != not equal

- \> greater than

- \< less than

- \>= greater than or equal to

- \< less than or equal to

- ? ternary operator