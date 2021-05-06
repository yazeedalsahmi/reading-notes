# Loops and iteration
## The For Loop
**A for loop** *repeats* until a specified condition evaluates to ***false***. Here’s its basic syntax:

`for (<initialization>; <condition>; <incremental expression>) {   code block // This is executed if condition evaluates to true}`
* **initialization** - used to declare new variables with the var keyword, typically used to initialize a counter variable (var i = 0).
* **condition** - An boolean expression to be evaluated before each loop iteration. If this expression evaluates to true, the inner commands will be executed.
* **incremental expression** - an expression evaluated at the end of each loop iteration. This is usually used to increment, decrement, or otherwise update the counter variable.
### Examples:
```
//Counting 1 to 6 for (var i = 1; i <= 6; i++) {  console.log(i);}//=&gt; 1//=> 2//=&gt; 3//=> 4//=> 5 //=>6

```
### The For/in Loop
The for/in loop is used to iterate through properties of an object. A for/in statement looks as follows:

`for (variable in object) {  statements}`
* **variable** - a different property name is assigned to this on each iteration.
* **object** - the object whose enumerable properties are iterated through.
### The While Loop
While loops are conditional loops where a condition is checked at the start of the iteration, and — if the condition is true — the statements are executed. Here’s the basic syntax of a while loop:

`while (condition) {  statement //code block to be executed as long condition is true.}`
* **condition** - the expression evaluated before each iteration through the loop. If this condition evaluates to true, the inner commands are executed. If the condition evaluates to false, then the inner statement won’t execute and the program carries on.
* **statement** - the code block to be executed as long as the condition evaluates to true.
Example:

`var i = 0;while (i < 3) {  console.log(i);  i++;}
//=>0//=>1//=>2`
