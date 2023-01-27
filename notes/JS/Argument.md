- Function arguments can be set to default to something:

```js
function sayHi(name = "Bob") {
	alert(`Hello ${name}`);
}

let userName = prompt("What is your name?"); 
sayHi(userName); // If it is empty, it'll alert "Hello Bob"
```