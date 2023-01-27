- You can label loops to later do [[Loop Breaks in JS]] better.

```js
// Break can usually only break out of the loop they are in. By using labels, we can break out of more. 
LABELNAME: for(i = 0, i < 10, ++i) {
	for(j = 0, j < 5, ++j) {
		break LABELNAME;
	}
}
```