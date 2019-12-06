
### Functions

- Invoking a function

**Function declarations**: are hoisted (function can be called before it is declared). Are assessable in the global namespace.

``` js
function example_function(parm1, parm2) {}
```

- Use case: Use Function Declarations when you will need to reuse the function multiple times. Because the function is accessible in the global namespace, the function will persist.

**Function expression**: are not hoisted. Are only accessible by calling the variable.

``` js
const example_function = function(parm1, parm2) {}
```

- Use case: Use Function Expressions when you need only need to perform an operation once. Function Expressions are anonymous, will not pollute the global namespace (limit the number of functions accessible program-wide). Function Expressions can help with application performance & security.

(https://www.freecodecamp.org/news/when-to-use-a-function-declarations-vs-a-function-expression-70f15152a0a0/)[When to use a function declaration vs. a function expression]

**Arrow Functions**:

**IIFE (immediately invoked function expressions)**:

(https://mariusschulz.com/blog/use-cases-for-javascripts-iifes)[Use Cases for JavaScript's IIFEs]

**Callbacks / Callback functions**:

(https://codeburst.io/javascript-what-the-heck-is-a-callback-aba4da2deced)[JavaScript: What the heck is a Callback?]

(https://stackoverflow.com/questions/52125594/what-is-the-difference-between-a-callback-function-helper-function-and-wrapper)[What is the difference between a callback function, helper function and wrapper function?]

**Helper Functions**:

**Wrapper Functions**:

**Hoisting**:

(https://developer.mozilla.org/en-US/docs/Glossary/Hoisting)[Hoisting]

**High Order Functions**:

### Concepts

**Mutable vs Immutable**

**mutating vs non-mutating**

**Separation of Concerns**:

**Modular Code**:

**Instances**:

**Scoping**:

- Global
- Local
- Lexical
- Block scope
- Scope pollution
- Tight scoping

### Loops

**For Loop**
**Nested Loop**
**While Loop**
**Infinite Loop**
**DO While**

### Objects

**Object Literal**