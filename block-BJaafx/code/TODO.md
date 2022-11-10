1. Using loops take 10 inputs from user and find the average of all the numbers.
<!-- let sum = 0
for (let i = 0; i < 10; i++) {
  var num = +prompt("Enter a number");
  sum += num;
}
let avg = sum/10; -->
alert (`The average of these number is ${avg}`)

2. What will be the output of the code below
<!-- // undefined -->

```js
let i = 0;
while (i < 3) {
  println('hi');
  i++;
}
```

3. Write a function named `getEvenSum` that accepts a parameter `max`. Return the sum of all even numbers. The value of max should default to 10.
<!-- // function getEvenSum(max = 10){
  let sum = 0
  for (i = 1 ; i<=max; i++){
    if (i % 2 == 0){
      sum += i;
    }
  }
  return sum;
}
getEvenSum() -->

4. Write a function named `getOddSum` that accepts a parameter `max`. Return the sum of all odd numbers. The value of max should default to 10.
<!-- // function getOddSum(max = 10){
  let sum = 0
  for (i = 1 ; i<=max; i++){
    if (i % 2 !== 0){
      sum += i;
    }
  }
  return sum;
}
getOddSum() -->

5. Write a function named `getProductOfDigits` that accepts a parameter `num`. It returns the product of all the digits in the number.
<!-- // function getProductOfDigits(num){
  let product = 1
  for (i = 0 ; i <= num; i++){
    if (num < 0){
      return "not a valid input"
    } else {
      product *= i;
    }
  }
  return product;
}
getProductOfDigits() -->

- If the input value is less than 0 return `not a valid input`
- For example if the input is `123` output should be `6`.

6. What will be the output of the following code below in multiple conditions? Explain with reason?

```js
function check(num) {
  if (num > 5) {
    return 'Bigger than 5';
  }

  if (num < 5) {
    return 'Smaller than 5';
  }

  return num;
}

check(10); //"Bigger than 5"
check(1); //"smaller than 5"
check(5); //5
```

7. What will be the output of the following code given below? Explain the reason?

```js
function getOutput(name) {
  if (name === 'Arya') return 'You are arya';
  if (name === 'John') return 'You are john';
  return 'Who are you';
}

getOutput('Arya'); // "You are arya"
getOutput('John'); // "You are john"
getOutput(); // "Who are you"
```

8. What will be the output of the following code given below? Explain the reason?

```js
function getOutput(name) {
  if (name === 'Arya') console.log('You are arya');
  if (name === 'John') console.log('You are john');
  return 'Who are you';
}

getOutput('Arya'); // Output  "you are arya" and it return "Who are you" 
getOutput('John'); // Output "You are john" and it return "Who are you"
getOutput(); // "Who are You"
```

9. Can a function have multiple return statement? Give one example if possible and explain the reason.
<!-- // Yes a function have multiple return statement , it is possible when condition applied in our function like 
function sayHello (name){
  if (name == "Anish"){
    return `Hello Anish`
  } else{
    return `Who are You`
  }
} -->

10. What is the difference between `for` loop and `while` loop. What are the different place you can use them? Explain with example.
<!-- // The 'for' loop used only when we already knew the number of iterations. The 'while' loop used only when the number of iteration are not exactly known. If the condition is not put up in 'for' loop, then loop iterates infinite times. If the condition is not put up in 'while' loop, it provides compilation error.  -->
<!-- For example, if we want to ask a user for a number between 1 and 10, we don't know how many times the user may enter a larger number, so we keep asking "while the number is not between 1 and 10". -->
