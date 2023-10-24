Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

Example:

```js
function hello() {
  var username = 'Arya';
}
console.log(useranme); // output
```

In above code we are looking for the variable named `usename`. There is no variable named `username` in the global scope. The variable is inside the function named `hello` and we can't access the variable defined inside a function from outside.

The above code will throw an error `Reference Error username is not defined`.

2. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

```js
{
  const username = 'Arya';
}
console.log(useranme); 
// In the above code we are looking for the variable named `username`. There is no variable named `username` in global scope . It is present inside block scope  but  const create a block scope  and in block scope  we  can't access variable  of block scope from outside. 

The above code will throw an error `Reference Error username is not defined`.
```

3. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

```js
if (true) {
  let username = 'Arya';
}
console.log(useranme); 
//  In the above code we are looking for the variable named `username`. There is no variable named `username` in global scope . It is present inside block scope  but  const create a block scope  and in block scope  we  can't access variable  of block scope from outside. 
The above code will throw an error `Reference Error username is not defined`.
```

4. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

```js
if (true) {
  var username = 'Arya';
}
console.log(useranme); 
//  In the above code we are looking for the variable named `username`. There is no variable named `username` in global scope . It is present inside curly braces and username is decleared with var keyword  it will allow to access username and we get value `Arya`. 
     Arya
```

5. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

```js
let username = 'John';
if (true) {
  var username = 'Arya';
}
console.log(useranme); 
//  In the above code we are looking for the variable named `username`.There is variable named `username` in global scope. as well as  we have same variable name inside curley braces so we declear same variable name twice it will give error.
    SyntaxError: Identifier 'username' has already been declared
```

6. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

```js
let username = 'John';
if (true) {
  let username = 'Arya';
}
console.log(useranme); 
//  In the above code we are looking for the variable named `username`.There is variable named `username` in global scope. as well as we have same variable name inside curley braces with which is decleared using let keyword which create block scope and  will execute variable which is decleared in global scope.
 "John"
```

7. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

```js
let username = 'John';
function sayHello() {
  let username = 'Arya';
}
sayHello();
console.log(useranme); 
//  In the above code we are looking for the variable named `username`.There is variable named `username` in global scope. as well as we have same variable name inside function which create a function scope so console log will execute username of global scope.
"John"
```

8. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

```js
for (var i = 0; i < 10; i++) {
  console.log(i, 'First');  
}
console.log(i, 'Second'); 


//  In the above code we are looking for the variable named `i` within for loop and  outside the loop first one will keep all the itteration and log from 0 to 9 and second one will count total no of i .
  0 'First'
  1 'First'
  2 'First'
  3 'First'
  4 'First'
  5 'First'
  6 'First'
  7 'First'
  8 'First'
  9 'First'
  10 'Second' 
```

9. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

```js
for (let i = 0; i < 10; i++) {
  console.log(i, 'First'); // output
}
console.log(i, 'Second'); // output
// In the above code we are looking for the variable named `i` within for loop and  outside the loop first one will keep all the itteration and log from 0 to 9 and second one will throw error bz it is decleared with let variable which create block scope  variable `i` will not get permission to enter within it.
  0 'First'
  1 'First'
  2 'First'
  3 'First'
  4 'First'
  5 'First'
  6 'First'
  7 'First'
  8 'First'
  9 'First'
  second:  Error i is not defined. 
```
