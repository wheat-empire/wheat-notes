## 2023-01-17

- Learnt [[What is JavaScript]].
	- I think the transpilations will be interesting - C
- Don't use callouts and code blocks in lists please - C
- This is how you put [[JS in HTML]].
- Make [[Readable Code Pls JS]]
- [[JS Variables]]
- Use `"use strict"` at the top of the code. Why? Common practice it seems.

## 2023-01-19

- The alert mentioned earlier is a [[Modal Types]]. We probably shouldn't use it to tell the people stuff 'cause it's intrusive but it's good for debugging and learning. - C
- `` ` ``  is the better `"` and `'`. It allows you to use `${var1}` syntax, and that's epic.

```js
let userName = prompt("What's your name?", "John");

// Using "" and '' is dumb and redudant because we have you use dumb and long syntax
alert("Your name is " + userName);

// Using `` is cool and epic because you can use ${var1} syntax 'cause it's cool and epic.
alert(`Your name is ${userName}`);
```

- Change things into strings using `String()`, into numbers using `Number()`, and into booleans using `Boolean()`. It doesn't produce errors, just NaN's and undefined's.
- Make constants that are pre-defined uppy-case please. e.g.

```js
// This constant is predefined. Hence, uppy-case
const AGE = 20;

// This constant is not predefined. We don't know it before running. Use mini-case.
const yourAge = prompt("What's your age?", 0);
```

- See [[Data Types JS]]
- 