#Javascript
##5 Primitives:
  1. boolean (true, false)
  2. numbers
  3. strings/text
  4. null - intentionally left valueless
  5. undefined - value yet to be defined

##Functions:
  -contains a block of statements that performs a set of operations
  -can be defined but not used until called
  -can contain arguments but not necessary
  -can declare functions two ways:
    1. declaration = loaded in script immediately regardless of placement in code
    2. expression = always contains var in front of it and not loaded at start; always end in a semicolon
  -return = stores information within the code, creating its own value
  -condole.log()= displays already set value in browser
  -arguments - variables inside function that you can change to produce different values, within brackets
  -parameters - what you set values as (maybe need clarification?)

##Loops:
  -loops allow you to repeat and iterate over time
  -for - run for iterated period of time; always have 3 parts: initialization, conditional, post-loop increments
  -while - continue only if condition is met
##Conditionals:
  -if, else, elseif statements
  -determines which code to run if certain conditions met
##Variables:
  -file pieces of data under a name
  -can be changed
  -are dependent on scope
  -must be initiated by keyword "var"
##Alerts and Prompts:
  -interactive
  -require user to respond
  -good for testing
  -natively returns a string
##Scope:
  -scope is the context and availability; extent of influence a variable has
  -global = accessible anywhere in the code
  -local = defined and accessible only within the function; when defined inside function, this is called hiding
  -variables defined in a local function can override a global variable
  -when a global variable is named inside a function without reassignment it with var, then it can override a variable with same name outside of function, this is called hoisting
##String concatenation:
  -combining characters and variables ex: "Hello " + yourName
  -have to add in spacing after a string, such as "Hello " or as own string added in between, such as num1 + " " + num2
##Methods (string, integer):
  -Note: all strings really an array
  - .charAt() - finds position of character in an array
  - .parseInt() - converts a string argument to an integer
  - .toString() - converts to a string
  - See [link] (https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Methods_Index)
##Math operators:
  - See [link] (https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators)
