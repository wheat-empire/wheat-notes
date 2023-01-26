- You can break loops in JS using `break`

```js
// This will alert us "Hello World" once.
while(true) {
	alert("Hello World");
	break;
}
```

- You can also use `continue` to only skip the current iteration

```js
// We will never see the hidden message :(
while(true) {
	alert("Hi");
	continue;
	alert("Hidden message")
}
```