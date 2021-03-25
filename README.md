# Conditionals and Comparisons Exercises
1. Write a function that takes two numbers `x` and `y` as arguments.
If `x` is greater than `y`, `console.log` 'X is greater than Y'.
If `y` is greater than `x`, `console.log` 'Y is greater than X'.
If `x` is equal to `y`, `console.log` 'X and Y are equal'.
```javascript
function compareNumbers(x, y) {
  // your code here
}
// compareNumbers(10, 3) => 'X is greater than Y'
```


2. Write a function that takes to strings `str1` and `str2` as arguments.
The function should `console.log` the longest string.
```javascript
function logLongest(str1, str2) {
  // your code here
}
// logLongest('backstreets back alright', 'bumbumbum') => 'backstreets back alright'
```


3. Write a function that takes one argument of an undetermined type called `foo`.
`console.log` the boolean true if `foo` has the type of string and is at least 5 characters long.
```javascript
function isLongString(foo) {
  // your code here
}
// isLongString(9000) => false
``` 

4. Write a function that takes three numbers `num1`, `num2`, and `product` as arguments.
`console.log` the boolean true if `num1` multiplied by `num2` is equal to `product`, otherwise `console.log` the boolean false.
If either `num1` or `num2` are 0, immediately `console.log` false.
```javascript
function checkProduct(num1, num2, product) {
  // your code here
}
// checkProduct(10, 5, 50) => true
```

5. Write a function that utilizes a switch statement and takes two numbers `customers` and `capacity` as arguments.
If `customers` meets or exceeds `capacity` `console.log` 'Theres gonna be a wait!'.
If the number of `customers` is less than 75% of `capacity`, `console.log` 'Step right this way!'.
If the number of `customers` is greater than 75% of `capacity`, `console.log` 'You got here just in time!'.
If there are no `customers` `console.log` "It's dead in here!".
```javascript
function capacityChecker(customers, capacity) {
  // your code here
}
// capacityChecker(4, 100) => 'Step right this way!'
```