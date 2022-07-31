1. Convert the function below into different forms of function expression.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}

// Your code goes here
let percentage = function percentage(marks, total) {
  return (marks * 100) / total;
}
   let percentage = function (marks, total){
  return (marks * 100) / total;
}

let percentage = (marks, total) => {
  return (marks * 100) / total;
};

let percentage = (marks, total) => {
  return (marks * 100) / total;
};
```

2. Write Function Declaration or Function Expression next to the function.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}
//  Function Declaration 
```

```js
let percentage = function percentage(marks, total) {
  return (marks * 100) / total;
};

//Function Expression 
```

```js
let percentage = function (marks, total) {
  return (marks * 100) / total;
};

// Function Expression  
```

```js
let percentage = (marks, total) => {
  return (marks * 100) / total;
};

//Function Expression  
```

```js
let percentage = (marks, total) => (marks * 100) / total;

//Function Expression  
```

3. Why is a function definition an expression in JavaScript? Give one example of function expression.
Ans. A function defination is a series of step to defined that we use the function keyword and also with that we can store any function in a variable because a function is a object and we can store objects in a variables.
```js
  function add(){

  }

  let obj = {};

  let add = function(){};

```

4. Why is a function call an expression in JavaScript?
```js 
 function add(a,b){
  return a + b; 
 };
 add(12,20); //32

 function addAgain(a,b){

 }

 addAgain(); //undefined 

//Function call always return a value and that's why a fuction is an expression.
```


5. Write VALID and INVALID next to each example below with the reason.

```js
function add(a, b) {
  return a + b;
}

let five = add(2, 3); // Valid 5
five = add; // Valid 
five = five(10, 11); // Valid 21
five = function () {
  return 'Hello';
}; // Valid 
```

6. What is the difference between function definition and function call? Explain with an example.
Ans. In function defination we can simply put our argument inside a function keyword but on the other hand we store our series of step inside a funciton and that along with that we put our function inside a variable because function is also a object and we can store object inside varibles.

```js 
 function add(){}; //defination 

 add(); //call 
 
```

7. What is the similarities between function definition and function call?
```js 
 // function defination is an expression (function is an object)
 // function call is also an expression (function call reuturn a value )
```

8. Is the code below valid or invalid. Explain with reason.

```js
function hello() {
  console.log('Hello World!');
}

hello.user = 'Sam'; // valid
 ```

9. What is higher order function explain with an example.
```js
// A  higher order function that accepts a function definaiton as an argument.
// A  higher order function that returns a fnction defination.
 
//Higher order function 
  function add(cb){  //HOF
    cb()
  }

  function add(){  //HOF
    function main(){}
      return main
  }
//Higher order function  
function filter Odd (arr, fn){
  console.log (fn(23), "inside filterOdd");
  return arr ;
}
```


10. Explain what is callback function. Why you can pass a function inside a function?
```js
//Because function is an expression in javscript so we can pass a function inside another function.
```