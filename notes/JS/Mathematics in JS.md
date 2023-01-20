- Most of it is about what you would expect.
- `+=`, `-=`, `*=`, and `/=` does this:

```js
let a = 0;

a += 1; // a is 1 now
a -= 2; // a is -1 now
a *= 3; // a is -3 now
a /= -1.5; //a is 2 now
```

- You can use `>=`, `<=`, `!=`, and `==` to test if two values have a certain relationship. 

```js
100 > 10; // true
100 != 10; // true
0 == false; // true, 0 is considered "false" when converted to boolean
"0" == false; // false, "0" is a string with something, so it is "true"
null == undefined; // true

"abacaba" < "abb"; // true, strings are compared using alphabetical 
```

- You can use `!==` and `===` to be even stricter

```js
0 === false; // false, even though 0 is considered false, they are not the same type
```