- There are 4 logic operators:
	- || (or)
	- && (and)
	- ! (not)
	- ?? (that one (it's actually called "nullish coalescing", but I mean wth) )
- They work like normal logic operators
- Here are some logic tables for your viewing pleasure:

| or | true | false |
| --- | --- | --- |
| true | true | true |
| false | true | false |

| and | true | false |
| --- | --- | --- |
| true | true | false |
| false | false | false |

| not | true | false |
| --- | --- | --- |
| | false | true |

- You can also use them for other things?

```js
// || finds the first true value
let orvar = null || 0 || 23; // This returns 23

// && finds the first false value
let andvar = 27 && "Hello World" && null; // This returns null

// ?? finds the first non-null-or-undefined value
let nullvar = null ?? undefined ?? "Hi"; // This returns "Hi"
```