- Functions are useful.
	- They are snippets of code you can call at any time.
- This is a function declaration:
	- These are retroactive. Put them anywhere in your script, and they can be called.
	- Note the [[Argument]]

```js
// This declares a function with the argument "name" which is like a variable
function sayHi(name) {
	alert(`Hello ${name}`);
}

let userName = prompt("What is your name?", "Bob");
sayHi(userName); // "Hello Bob"
```

- Functions are also values

```js
// This declares a function with the argument "name" which is like a variable
function sayHi(name) {
	alert(`Hello ${name}`);
}

let userName = prompt("What is your name?", "Bob");
sayHi(userName); // "Hello Bob"

let funky = sayHi;

funky(userName); // "Hello Bob"
```

- Variables inside functions cannot be used outside of it, but variables outside can be used inside functions.
	- A quirk happens when the variable is defined outside of a function, but is modified in the function. If that's the case, then it changes.

```js
let x = 1;

function xIncrease() {
	++x;
}

xIncrease()
// x is now two, not one
```

- You can return values using functions:

```js
let func = name(1, 2);

function name(val1, val2) {
	// Like break, return will stop the function
	return val1 + val2;
}

// This should return 3.
alert(func);
```

- There's also a thing called function expressions
	- This is not retroactive

```js
let name = function(arg1) {
	// shtuff
};

name();
```

- You can also include functions as the argument of a function (for some reason)

```js
function adder(x, y) {
	alert(x+y)
}

function sayHi(func) {
	alert("Hello world");
	let x = 3;
	let y = 7;
	func(x, y);
}

sayHi(adder);
```