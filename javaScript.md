# Javascript Concepts
- syntax parsers and compilers are programs that read the instructions given in the code (browsers)
- lexical environment, where you write something eg. a variable "sits" inside a function
- execution context, wrappers that manage written code
- name-value pairs, a name mapped to a value (address = 1 street)
- object is a collection of name-value pairs

Javascript Engine - Execution Context for browser
- global execution context (accessible everywhere to everything in code)
- global is variables/code that exists outside a function
  - js engine creates a global object called "window" inside the browser
  - js engine creates a special variable called "this" which is same as "window" object inside browser

Hoisting
- allows js to have functions and variables declared out of sequence in the execution order (top down)
  - functions can be declared after they are executed, results in an "undefined" value
- Creation phase, setting memory space for execution context 
  - before execution js engine parses variables and funtions and stores them in memory
  - entire function (code) is placed in memory space (function name and code)
  - doesn't store variables values in memory until execution phose, uses a placeholder value called "undefined"
  - "undefined" is a js variable value that isn't set in memory
- Execution phase, executes code line by line, reads variable values

Single Threaded Synchronous Execution Behaviour
- single threaded, one js command executed at a time
- synchronous, one line of code executed at a time in the order that it appears
  - one thing is happening at a time

#### References
Tony Alicea, JavaScript: Understanding the Weird Parts\
https://www.youtube.com/watch?v=Bv_5Zv5c-Ts
