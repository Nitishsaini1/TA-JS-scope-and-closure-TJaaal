1. Convert the function below into different forms of function expression.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}

// Your code goes here
let percentage = function (marks, total){
  return (marks * 100) / total;
}

let percentage = (marks, total) => {
  return (marks * 100) / total;
};
```

2. Write Function Declaration or Function Expression next to the function.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}
// Your answer

let percentage = function (marks, total){
  return (marks * 100) / total;
}
```

```js
let percentage = function percentage(marks, total) {
  return (marks * 100) / total;
};

//my code 
function percentage(marks, total) {
  return (marks * 100) / total;
};
```

```js
let percentage = function (marks, total) {
  return (marks * 100) / total;
};

//my code

function percentage(marks, total) {
  return (marks * 100) / total;
};
```

```js
let percentage = (marks, total) => {
  return (marks * 100) / total;
};

//my code

function percentage(marks, total) {
  return (marks * 100) / total;
};
```

```js
let percentage = (marks, total) => (marks * 100) / total;

//my code

function percentage(marks, total) {
  return (marks * 100) / total;
};
```

3. Why is a function definition an expression in JavaScript? Give one example of function expression.
Ans. A function defination is a series of step to defined that we use the function keyword and also with that we can store any function in a variable because a function is a object and we can store objects in a variables.

4. Why is a function call an expression in JavaScript?
Ans. function is an object in javascript when we stored that into a variable it becomes function expression "reference is knowing the series of step". "Execution is excuting those series of step."


5. Write VALID and INVALID next to each example below with the reason.

```js
function add(a, b) {
  return a + b;
}

let five = add(2, 3); // Answer
five = add; // Answer
five = five(10, 11); // Answer
five = function () {
  return 'Hello';
}; // Answer
```

6. What is the difference between function definition and function call? Explain with an example.
Ans. In function defination we can simply put our argument inside a function keyword but on the other hand we store our series of step inside a funciton and that along with that we put our function inside a variable because function is also a object and we can store object inside varibles.

7. What is the similarities between function definition and function call?
Ans. There are few similarities in both of them we can say like both works same like they contains a series of step.

8. Is the code below valid or invalid. Explain with reason.

```js
function hello() {
  console.log('Hello World!');
}

hello.user = 'Sam'; // Invalid
//Because we haven't define that user.  
```

9. What is higher order function explain with an example.
Ans. A function that accepts a function definaiton as an argument is known as higher order function.
Example
```js
//Higher order function 
  let isOdd = function(num){
    return num%2 !== 0;
  } 

//Higher order function  
function filter Odd (arr, fn){
  console.log (fn(23), "inside filterOdd");
  return arr ;
}
```


10. Explain what is callback function. Why you can pass a function inside a function?
```js
//isOdd (call back function)
filterOdd ([1,2,3,6,7], isOdd);

```