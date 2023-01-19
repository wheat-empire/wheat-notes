- A modal is that popup thing that takes away all your control from the website.
- There are three types:
	- `alert(message)` creates a simple text modal
	- `prompt(message, [default])` creates a modal with a space to write in
	- `confirm(message)` creates an modal that takes boolean for an output.

```js
let hi = "Hello World";

// This creates a modal with "Hello World"
alert(hi);

// This creates a prompt saying "Hello World". Default answer is "Hi", although you can say anything. promptOutput is anything you type in.
let promptOutput = prompt(hi, "Hi");
alert(promptOutput);

// This creates a confirm modal saying "Hello World". If you click okay, we get a true. If you press cancel, you get a false.
let confirmOutput = confirm(hi);
alert(confirmOutput);
```

- See a demo at https://codepen.io/MEGANUBS/pen/ZEjaKzx