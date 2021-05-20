# Function in JavaScript :
**A JavaScript function** is a *block of code* designed to perform a particular task.it should take some input and return an output where there is some obvious relationship between the input and the output. To use a function, you must define it somewhere in the scope from which you wish to call it.
## Why Use Function :
1. You can reuse code: Define the code once, and use it many times.

2. You can use the same code many times with different arguments, to produce different results.
## How write Function in JavaScript  :
***A JavaScript function*** is defined with the `function` keyword, followed by a **name**, followed by parentheses `()`.

Function names can contain letters, digits, underscores, and dollar signs (same rules as variables).

***The parentheses*** may include *parameter* names separated by commas:
(parameter1, parameter2, ...)

The code to be executed, by the function, is placed inside **curly brackets:** `{}`.

`
function name(parameter1, parameter2, parameter3) {
  return // code to be executed
}
`

* Function parameters are listed inside the parentheses () in the function definition.

* Function arguments are the values received by the function when it is invoked.

* Inside the function, the arguments (the parameters) behave as local variables.
* When JavaScript reaches a return statement, the function will stop executing.

* If the function was invoked from a statement, JavaScript will "return" to execute the code after the invoking statement.

* Functions often compute a return value. The return value is "returned" back to the "caller".

Ex :
```
var x = myFunction(10, 5);   // Function is called, return value will end up in x

function myFunction(a, b) {
  return a / b;             // Function returns the product of a and b
}
```




 