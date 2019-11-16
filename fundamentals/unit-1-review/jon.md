Create a function that takes in an array of strings.
and returns an array where the last index of each string is uppercased
- while loop
- build-in method
```js
input => ['lowercase', 'uppercase', 'index', 'method', 'function'];
output => ['lowercasE', 'uppercasE', 'indeX', 'methoD', 'functioN'];
```

Create a function that takes in an array of numbers, and return only the numbers that are even after 1 is added to their value.
Solve using:
 - while loop
 - for loop

```js
input => [2,5,7,8,1,2,57,99]
output => [5,7,1,57,99]
```

Create a function that given a string of odd length, return the string length 3 from its middle, so "Candy" yields "and". The string length will be at least 3.


```js
input =>'Candy' 
output => 'and'
input =>'and'
output => 'and'
input => 'solving'
output => 'lvi'
```

Create a function that takes two arguments an integer and either 'min' or 'sec' that converts minutes to second or seconds to minutes.
```js 
input => 5,'min'
output => 300
input => 600, 'sec'
output => 10 
```

Create a function that takes in an array of numbers, returns all the non-zero numbers in front of all the zeros in the array, then return the new array and the count of non-zero numbers.

```js
input => [2,0,3,0,5,0,7,1,0]
output => [2,3,5,7,1,0,0,0,0,], 4
```

Create a function that takes in array of integer, find the two numbers that when multiplied together give the greatest product, and return that product.

```js
input => [2,7,5,8,3,9,1]
output => 72
```

Create a function that returns the number of argument it was called with.

```js
input => howManyArgs()
output => 0
input => howManyArgs(1,3,5)
output => 3
input => howManyArgs(false,'maybe','perhaps', 'nah bruh',true)
output => 5
```
Create a function that converts an object into an array, where each element represents a key-value pair.

```js
input => { a: 1, b: 2 }
output => [["a", 1], ["b", 2]]
input => { shrimp: 15, tots: 12 } 
output => [["shrimp", 15], ["tots", 12]]
input => {}
output => []
  ```

Create a function that takes a string and calculates the number of letters and digits within it. Return the result as an object.

```js
input =>"Hello World" 
output => {"LETTERS":  10, "DIGITS": 0}
input => "H3ll0 Wor1d"
output => {"LETTERS":  7, "DIGITS": 3}
input =>"149990" 
output => {"LETTERS": 0, "DIGITS": 6}
```
Create a function that given an object containing the names and ages of a group of people, return the name of the oldest person.

```js
input => {
  Emma: 71,
  Jack: 45,
  Amy: 15,
  Ben: 29}
output => "Emma"

input => {
  Max: 9,
  Josh: 13,
  Sam: 48,
  Anne: 33}
output => "Sam"
```