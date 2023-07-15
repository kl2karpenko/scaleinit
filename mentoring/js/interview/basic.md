### Guess the outputs of the following codes:

```js
var x = 23;

(function(){
	var x = 43;
	(function random(){
		x++;
		console.log(x);
		var x = 21;
	})();
})(); 
```

### Guess the outputs of the following codes:

```js
function func1() {
	setTimeout(() => {
		console.log(x);
		console.log(y);
	}, 3000);

	var x = 2;
	let y = 12;
}
func1();

// Code 2:

function func2() {
	for (var i = 0; i < 3; i++) {
		setTimeout(() => console.log(i), 2000);
	}
}
func2();

// Code 3:

(function () {
	setTimeout(() => console.log(1), 2000);
	console.log(2);
	setTimeout(() => console.log(3), 0);
	console.log(4);
})();
```

### Guess the outputs of the following code:

```js
// Code 1

let hero = {
	powerLevel: 99,
	getPower(){
		return this.powerLevel;
	}
}

let getPower = hero.getPower;

let hero2 = {powerLevel:42};
console.log(getPower());
console.log(getPower.apply(hero2));

// Code 2

const a = function(){
	console.log(this);

	const b = {
		func1: function(){
			console.log(this);
		}
	}

	const c = {
		func2: ()=>{
			console.log(this);
		}
	}

	b.func1();
	c.func2();
}

a();



// Code 3

const b = {
	name:"Vivek",
	f: function(){
		var self = this;
		console.log(this.name);
		(function(){
			console.log(this.name);
			console.log(self.name);
		})();
	}
}
b.f();

```
### Guess the outputs of the following code:

```js

(function(a){
  return (function(){
    console.log(a);
    a = 23;
  })()
})(45);

```

### Guess the outputs of the following code:

```js
const x = {};
const y = { name: 'Ronny' };
const z = { name: 'John' };
x[y] = { name: 'Vivek' };
x[z] = { name: 'Akki' };
console.log(x[y]);

// Code 1:

function runFunc() {
	console.log(`1${1}`);
	console.log('A' - 1);
	console.log(`${2}-2` + `2`);
	console.log('Hello' - 'World' + 78);
	console.log('Hello' + '78');
}
runFunc();

// Code 2:

const a = 0;
const b = false;
console.log(a == b);
console.log(a === b);
```

### Guess the outputs of the following code:

```js

// Each time bigFunc is called, an array of size 700 is being created,
// Modify the code so that we don't create the same array again and again

function bigFunc(element){
  let newArray = new Array(700).fill('♥');
  return newArray[element];
}

console.log(bigFunc(599)); // Array is created
console.log(bigFunc(670)); // Array is created again
```

### How to empty an array in JavaScript?

### Write a function that will check if a number is an integer

### Write a function that would allow you to do this?

```js
const addSix = createBase(6);
addSix(10); // returns 16
addSix(21); // returns 27
```

### Given two strings, return true if they are anagrams of one another

For example: Mary is an anagram of Army

### How would you use a closure to create a private counter? Give an example and write a code to show example