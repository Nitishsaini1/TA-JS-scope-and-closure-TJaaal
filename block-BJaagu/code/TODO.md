Find the output of the code snippets below:

```js
console.log(numA + numB); //NAN
var numA = 21,
  numB = 30;
```

Find the output of the code snippets below:

```js
console.log(numA + numB); // 'numA' has already been declared
let numA = 21,
  numB = 30;
```

Find the output of the code snippets below:

```js
let numA = 21,
  numB = 30;
console.log(numA + numB); //'numA' has already been declared
```

Find the output of the code snippets below:

```js
console.log(sayHello()); // OUTPUT
function sayHello() {
  console.log("Hey");
}
function sayHello() {
  console.log("Hello");
}
//Hello
//undefined
```

Find the output of the code snippets below:

```js
let username = "Tyrion";
sayHello(); // OUTPUT
function sayHello() {
  console.log(username);
}
```

Find the output of the code snippets below:

```js
sayHello(); // 'username' has already been declared
let username = "Tyrion";
function sayHello() {
  console.log(username);
}
```

Find the output of the code snippets below:

```js
let username = "Tyrion";
sayHello(); // 'username' has already been declared
let sayHello = () => {
  console.log(username);
};
```

Find the output of the code snippets below:

```js
sayHello(); // 'username' has already been declared
let username = "Tyrion";
let sayHello = () => {
  console.log(username);
};
```

Find the output of the code snippets below:

```js
sayHello(); // 'sayHello' has already been declared
var username = "Tyrion";
let sayHello = () => {
  console.log(username);
};
```

Find the output of the code snippets below:

```js
var username = "Tyrion";
sayHello(); // 'sayHello' has already been declared
let sayHello = () => {
  console.log(username);
};
```

Find the output of the code snippets below:

```js
var username = "Tyrion";
let sayHello = () => {
  console.log(username);
  var username = "John";
};
sayHello(); //  'sayHello' has already been declared
```

Find the output of the code snippets below:

```js
var username = "Tyrion";
let sayHello = () => {
  var username = "John";
  console.log(username);
};
sayHello(); // 'sayHello' has already been declared
```

Find the output of the code snippets below:

```js
var username = "Tyrion";
let sayHello = () => {
  console.log(username);
  let username = "John";
};
sayHello(); // 'sayHello' has already been declared
```