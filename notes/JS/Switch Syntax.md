- You could use `switch` instead of `if`

```js
// If var1 = value1, then it does the first thing. From then on guess what they do.
// Also, if you don't break them, then they will just continue until they meet a break.
switch(var1) {
	case 'value1':
		// Something
		break;
	case 'value2':
		// Something
		break;
	default:
		// Something
		break;
}

// e.g.
let userName = "DefNotEddie";

switch(userName) {
	case "DefNotEddie":
		// since userName is DefNotEddie, this will be alerted.
		alert("You having fun on holiday?");
	case "Mspicata":
		// because the eddie bit has no break, this will run as well.
		// if you were me, you would only see this bit.
		// if you were ed, you would see both ed and my bits.
		alert("Hello World!");
		break;
	default:
		// it defaults to this if it is neither.
		alert("Who you?");
		break;
}
```