
### Functions

- Function declarations: are hoisted (function can be called before it is declared). Are assessable in the global namespace.

``` js
function example_function(parm1, parm2) {}
```

- Function expression: are not hoisted. Are only accessible by calling the variable.

``` js
const example_function = function(parm1, parm2) {}
```

(https://www.freecodecamp.org/news/when-to-use-a-function-declarations-vs-a-function-expression-70f15152a0a0/)[When to use a function declaration vs. a function expression]