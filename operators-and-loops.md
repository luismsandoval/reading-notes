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

## Loops and iteration

Loops allow for a line of code to be ran repeatedly. There are various kinds of loops but today we will focus on `for statements` and `while statements`.

### `for` statement

This loop repeats until a specific condition evaluates it to `false` 

```
for ([initialExpression]; [conditionExpression]; [incrementExpression])
  statement
```

1. The `initialExpression` is executed. This initilizes loop counters and can also declare variables.

2. The `conditionExpression` is then evaluated. If the value is true, the loop statement executes. If false, the loop terminates. Note: leaving this empty will result in the condition to be assumed true.

3. The `statement` executes.

4. Then if present, the `incrementExpression` executes

### `while` statement

This statement executes as long as a specified condition remains true.

```
while (condition)
  statement
```

If the `condition` becomes false, the `statement` will stop executing.

```
let n = 0;
let x = 0;
while (n < 3) {
  n++;
  x += n;
}
```

This `while loop` runs as long as `n` is less than `3`. The loop will stop executing after 3 iterations because at that point `n` will not be less than `3`.

NOTE: Make sure that the condition in your `while` loop becomes false, otherwise it will run infinite times and crash your browser. Here is an example of an infinite loop:

```
// Infinite loops are bad!
while (true) {
  console.log('Hello, world!');
}
```