- Instead of using function expressions, we can use arrow functions

```js
// Uh, what I written should be enough. Just learn the syntax :-)
(argument) => dothis

// eg
const sum = (x, y) => x + y;

alert(sum(2, 5));
```

- Note that the argument part can be empty if you don't need to use it.
- Note that it will return anything in the dothis section
- You can also multiline:

```js
(argument) => {
	// Please note that multiline need a return
	return random;
}
```