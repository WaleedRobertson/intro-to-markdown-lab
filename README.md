# Writing a Function in JavaScript

In JavaScript, functions are blocks of reusable code. They allow you to bundle functionality, make it more readable, and avoid repetition. Here's a brief tutorial on writing an arrow function in JavaScript.

## 1. Basic syntax
```javascript
const functionName = (params) => {
  // code to be executed
}
```
**const**: const should be used whenever a function expression is assigned to a variable.
**The function name**: The name you choose for the function.
Parameters: Optional comma separated parameters. This is the data passed into the function. If there are no parameters, the () is still required.
The arrow syntax: Indicates that this will be a function.
The body: The statements that make up the function itself. Surrounded by curly braces.

___Example:___
```javascript
const greet = (name) => {
  console.log("Hello, " + name + "!");
}
```
> Tip: Functions often perform actions, so naming with a verb can make it clear what the function does. Examples include fetchData( ), calculateArea( ), or printReport( ). 

## 2. Calling a function

To execute the function, you *call* or *invoke* it by using its name followed by parentheses.

___Example:___
```javascript
greet('Alice'); // Outputs: Hello, Alice!
```
## 3. Return values

Functions can process data input and output a value using the *return* keyword.

___Example:___
```javascript
const addNums = (numA, numB) => {
  return numA + numB
}

const total = addNums(2, 4);

console.log(total) // Expected value: 6
```
For more information on functions and how they are used in JS, check out the MDN docs
[MDN Link](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Functions)

This text is ***bold and italicized***. This text is also ___bold and italicized___.

+ Item 1
- Item 2
  * Subitem 2.1
  * Subitem 2.2
    * Subitem 2.2.1

1. First item
2. Second item
   1. Subitem 2.1
   2. Subitem 2.2

Use the `console.log()` function to print values to the console.

```javascript
const printItem = (item) => {
  console.log(item);
}
```
```javascript
const printItem = (item) => {
  console.log(item);
}
```

[Google](https://www.google.com)

This is [a reference][example].

[example]: http://www.example.com/

> This is a blockquote.

> First level of blockquote.
>> Nested blockquote.
>>> Another nested blockquote.

![some alt text](www.url_to_an_image.com/image)

![Computer with Code]()

![Computer with Code](/modular-curriculum-all-courses/intro-to-markdown-lab/exercise/assets/james-harrison-unsplash.jpg)






![Mother and daughter in winter clothes](./Assets/pexels-zeng-jinwen-679366437-20852606.jpg)

- [x] Task 1
- [ ] Task 2
- [ ] Task 3

This text has been ~~redacted~~. 
