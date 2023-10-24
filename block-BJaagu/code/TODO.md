Find the output of the code snippets below:

```js
console.log(numA + numB); //NAN
var numA = 21,
  numB = 30;
```

Find the output of the code snippets below:

```js
console.log(numA + numB); //OUTPUT
let numA = 21,
  numB = 30;
```

Find the output of the code snippets below:

```js
let numA = 21,
  numB = 30;
console.log(numA + numB); //ReferenceError: numA is not defined
```

Find the output of the code snippets below:

```js
console.log(sayHello()); // undefined
function sayHello() {
  console.log("Hey");
}
function sayHello() {
  console.log("Hello");
}
```

Find the output of the code snippets below:

```js
let username = "Tyrion";
sayHello(); // Tyrion
function sayHello() {
  console.log(username);
}
```

Find the output of the code snippets below:

```js
sayHello(); // ReferenceError: username is not defined
let username = "Tyrion";
function sayHello() {
  console.log(username);
}
R
```

Find the output of the code snippets below:

```js
let username = "Tyrion";
sayHello(); // ReferenceError: sayHello is not defined
let sayHello = () => {
  console.log(username);
};

```

Find the output of the code snippets below:

```js
sayHello(); // ReferenceError: sayHello is not defined
let username = "Tyrion";
let sayHello = () => {
  console.log(username);
};
```

Find the output of the code snippets below:

```js
sayHello(); // ReferenceError: sayHello is not defined
var username = "Tyrion";
let sayHello = () => {
  console.log(username);
};
```

Find the output of the code snippets below:

```js
var username = "Tyrion";
sayHello(); // ReferenceError: sayHello is not defined
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
sayHello(); // undefined
```

Find the output of the code snippets below:

```js
var username = "Tyrion";
let sayHello = () => {
  var username = "John";
  console.log(username);
};
sayHello(); // John
```

Find the output of the code snippets below:

```js
var username = "Tyrion";
let sayHello = () => {
  console.log(username);
  let username = "John";
};
sayHello(); // ReferenceError: Cannot access 'username' before initialization
```