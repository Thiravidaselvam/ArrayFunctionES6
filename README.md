# ArrayFunctionES6
Array Functions

map():
The map() method creates a new array by calling a provided function on each element of the original array. It is often used to transform data or render lists of elements.
Example:

jsx
Copy code
const numbers = [1, 2, 3, 4, 5];

const doubledNumbers = numbers.map((number) => number * 2);

console.log(doubledNumbers); // Output: [2, 4, 6, 8, 10]
filter():
The filter() method creates a new array containing all the elements from the original array that meet a certain condition specified in a callback function.
Example:

jsx
Copy code
const numbers = [1, 2, 3, 4, 5];

const evenNumbers = numbers.filter((number) => number % 2 === 0);

console.log(evenNumbers); // Output: [2, 4]
reduce():
The reduce() method is used to accumulate a single value by applying a function to each element of the array.
Example:

jsx
Copy code
const numbers = [1, 2, 3, 4, 5];

const sum = numbers.reduce((accumulator, currentNumber) => accumulator + currentNumber, 0);

console.log(sum); // Output: 15
forEach():
The forEach() method executes a provided function once for each array element.
Example:

jsx
Copy code
const numbers = [1, 2, 3, 4, 5];

numbers.forEach((number) => {
  console.log(number);
});
// Output: 1 2 3 4 5
find():
The find() method returns the value of the first element in the array that satisfies the provided testing function.
Example:

jsx
Copy code
const numbers = [1, 2, 3, 4, 5];

const foundNumber = numbers.find((number) => number === 3);

console.log(foundNumber); // Output: 3
These are just a few examples of commonly used array methods in React. There are many other array methods available in JavaScript that you can use based on your specific use case.
