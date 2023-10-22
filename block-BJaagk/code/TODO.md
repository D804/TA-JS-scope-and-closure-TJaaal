1. Convert the function below into different forms of function expression.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}

// function Expression
 let percent = function percentage(marks , total) {
          return (marks*100) /total; 
 }
 percent(400,500);

//  Anonymous Function
let percentage =  function (marks, total) {
  return (marks*100)/total;
}

 percentage(400,500);

// Arrow function with curly bracket
let percentage = (marks,total) => {
     return (marks*100)/total; 
}
    percentage(400,500);

//  Arrow function without curley bracket
let percentage = (marks,total) => (marks*100)/total; 
```

2. Write Function Declaration or Function Expression next to the function.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}
// Function Declaration
```

```js
let percentage = function percentage(marks, total) {
  return (marks * 100) / total;
};
// function Expression
```

```js
let percentage = function (marks, total) {
  return (marks * 100) / total;
};
// Anonymous function Expression
```

```js
let percentage = (marks, total) => {
  return (marks * 100) / total;
};
// Arrow function with curly bracket
```

```js
let percentage = (marks, total) => (marks * 100) / total;
// Arrow function
```

3. Why is a function definition an expression in JavaScript? Give one example of function expression.
<!--  -->

4. Why is a function call an expression in JavaScript?

5. Write VALID and INVALID next to each example below with the reason.

```js
function add(a, b) {
  return a + b;
}

let five = add(2, 3); //  Valid because function taking argument a and b and returning  addition of both of them .
five = add; // valid because its store the function refrence.
five = five(10, 11); // valid  return will return sum of them.
five = function () {
  return 'Hello';
}; // Valid code
```

6. What is the difference between function definition and function call? Explain with an example.
 function defination means defining function and steps and function call means calling function or execution of store steps.
 <!-- Function Defination -->
  function getSum (numA,numB) {
    return numA+numB;
  }
  <!-- Function call -->
  getSum(20,30);

7. What is the similarities between function definition and function call?
 function name is similar in function defination and function call 

8. Is the code below valid or invalid. Explain with reason.

```js
function hello() {
  console.log('Hello World!');
}

hello.user = 'Sam'; // valid 
```

9. What is higher order function explain with an example.

<!-- In JavaScript, a higher-order function is a function that takes one or more functions as arguments, returns a function as its result,  -->

10. Explain what is callback function. Why you can pass a function inside a function?
<!-- Functions that Take Functions as Arguments is known as callback function -->
