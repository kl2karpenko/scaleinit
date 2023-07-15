### Write the code given If two strings are anagrams of one another, then return true.

```js 
var firstWord = "Deepak";
var secondWord = "Aman";

isAnagram(wordOne, wordTwo); // true

function isAnagram(one, two) {
//Change both words to lowercase for case insensitivity..
	var a = one.toLowerCase();
	var b = two.toLowerCase();

// Sort the strings, then combine the array to a string. Examine the outcomes.
	a = a.split("").sort().join("");
	b = b.split("").sort().join("");

	return a === b;
}
```

### Write the code to find the vowels

```js

const findVowels = str => {
	let count = 0
	const vowels = ['a', 'e', 'i', 'o', 'u']
	for(let char of str.toLowerCase()) {
		if(vowels.includes(char)) {
			count++
		}
	}
	return count
}

```

### Make this syntax possible:

```
var obj = {
  name: "Kolya",
  age: 30
};

console.log(obj + 6); // 36
console.log('Hi ' + obj); // 'Hi Kolya'
```

### Create a function to shallow compare of 2 objects passed to it;

### Create a function to deep compare of 2 objects passed to it;

### Make this syntax possible:

```
var objMath = {};
var a = objMath.set(12).plus(3).minus(6); // 9
```

### Make this syntax possible:

```
var a = add(2)(3)(4); // 9
```

## Guess the outputs for each Code

```js
// Code 1

function Rabbit() { }
Rabbit.prototype = { eats: true };

var rabbit = new Rabbit();

Rabbit.prototype = {};

alert(rabbit.eats);

// Code 2

function Rabbit(name) { }
Rabbit.prototype = { eats: true };

var rabbit = new Rabbit();

Rabbit.prototype.eats = false; // (*)

alert(rabbit.eats);

// Code 3
function Rabbit(name) { }
Rabbit.prototype = { eats: true };

var rabbit = new Rabbit();

delete Rabbit.prototype.eats; // (*)

alert(rabbit.eats);

```

### Write a sum function that will return the sum of any number of numbers. The function should work like this:

```js sum(2)(5)(6)(7)(2)(3)(4)( ); // 29 sum(56)(-10)(3)(1)( ); // 50 ```

Do the same so that you can work without empty brackets at the end: ```jssum(2)(5)(6)(7)(2)(3)(4)``` - like this.

## Events

### 1

Prohibit leading some characters in the input (for example, a, b, c, d, e).
Any other characters must be entered, but these simply will not appear, no matter how much we press them.

### 2

Input given. When entering a number into it, it must separate triples of numbers with spaces (as you type).

### 3

Given 4 inputs. Make it so that as soon as 2 characters are entered into the first input, the input focus moves to the second input, then to the third, and then to the 4th.

### 4

Given a table of arbitrary size. By clicking on a table cell, this cell is painted with a red background ("activated"). Make it so that if 5 cells in a row are activated horizontally or vertically, the table is locked (that is, no more cells can be activated) and the message "activations completed" is displayed.

P.S. The copy and paste trick needs to be caught, as well as other workarounds.