1. What is the difference between the two `sum` function given below?

```js
// <!-- The main difference betweeen both "sum" function is return and console.log in our first function it return the output of a + b  next line whatever it is but in second it is undefined. -->
// first
function sum(a, b) {
  return a + b;
}

// second
function sum(a, b) {
  console.log(a + b);
}
```


2. If we store the returned value of both functions above in variable `first` and `second` what will be the value of `first` and `second`.
<!-- After stored the return value , The value of first and second will be same (a + b); -->


3. What will be the output when you call above `sum` function (first) with three parameter like `sum(12, 24, 35)`. Explain why?
<!-- // The output will based on First two arguments like (a + b) because previously we set only two parameters  -->

4. Can you store the first `sum` function in a variable named `add`. If yes why? If no why?
 <!-- Yes we can store the any function in variable because function is an expression it  should on right side of eqaul to and also it is a value because it is in an object. -->

5. Declare a function named `sayHello` that accepts a parameter `name` and returns the name like `Hello Arya`.
<!-- function sayHello(name){
  return (`Hello ${name}`)
} -->

6. What will be the output of the function below and why?
<!-- `HelloJohn` -->

```js
let userName = 'John';

function showMessage() {
  let message = 'Hello ' + userName;
  return message;
}

showMessage();
```

7. What will be the output for `Output1` `Output2` and `Output3` in the code below.

```js
let userName = 'John';

function showMessage() {
  let message = 'Hello ' + userName;
  return message;
}

// alert(userName); "John"

// showMessage(); "Hello John"

// alert(userName); "John"
```
// 
8. What is a Anonymous Function give example of three functions.
<!-- //An anonymous function is a function that was declared without any named identifier to refer to it. As such, an anonymous function is usually not accessible after its initial creation. example :- let sayHello = function(){} and let checkAge = (a) => {}, let declare = (b) => b + 2; -->


9. Can function declaration be a Anonymous Function? Explain
<!-- //A function expression/Anonymous Function is very similar to and has almost the same syntax as a function declaration . The main difference between a function expression and a function declaration is the function name, which can be omitted in function expressions to create anonymous functions -->

10. Give 5 example of good naming convention for defining a function. You can read the details below to do that.
<!-- function sayHello(){};
function checkBmi(){};
function declareResult(){};
function isItornot(){};
function createFun(){}; -->


```md
Functions are actions. So their name is usually a verb. It should be brief, as accurate as possible and describe what the function does, so that someone reading the code gets an indication of what the function does.

It is a widespread practice to start a function with a verbal prefix which vaguely describes the action. There must be an agreement within the team on the meaning of the prefixes.

For instance, functions that start with "show" usually show something.

Function starting with…

"get…" – return a value,
"calc…" – calculate something,
"create…" – create something,
"check…" – check something and return a boolean, etc.
```
