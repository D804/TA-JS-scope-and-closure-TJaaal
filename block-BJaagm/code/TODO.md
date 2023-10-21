1. What does thread of execution means in JavaScript?
```
 Thread of execution means line by line execution of program.
```
2. Where the JavaScript code gets executed?
```
 Javascript code get executed in the javaScript engine.
```
3. What does context means in Global Execution Context?
 ```
   When a program execute its create a  global execution means it is running on js engine.
```
4. When do you create a global execution context.
   ```
    We create a global execution when we execute program.
```
5. Execution context consists of what all things?
```
    Execution context consist of (1) Memory which consist data (2) computation or execution
```
6. What are the different types of execution context?
   ```
    There are two type of execution context
    (1) Global execution Context
    (2) Function execution context
  ```
7. When global and function execution context gets created?
   ```
   When  entire program execute it will create Global Execution Context and hen function execute it will create Function execution context.  
  ```
8. Function execution gets created during function execution or while declaring a function.
   ```
   Function execution gets created during function execution.
```
9. Create a execution context diagram of the following code on your notebook. Take a screenshot/photo and store it in the folder named `img`. Use `![](./img/image-name.png)` to display it here.



```js
var user = "Arya";

function sayHello(){
  return `Hello ${user}`;
}

var userMsg = sayHello(user);
```

<!-- Put your image here -->
![](../img/first%20pr1.PNG);



```js
var marks = 400;
var total = 500;

function getPercentage(amount, totalAmount){
  return (amount * 100) / totalAmount;
}

var percentageMarks = getPercentage(marks, total);
var percentageProfit = getPercentage(400, 200);
```

<!-- Put your image here -->

![](../img/first%20pr%202.PNG);



```js
var age = 21;

function customeMessage(userAge){
  if(userAge > 18){
    return `You are an adult`;
  }else {
    return `You are a kid`;
  }
}

var whoAmI = customeMessage(age);
var whoAmIAgain = customeMessage(12);
```

<!-- Put your image here -->

![](../img/first%20pr%203.PNG);