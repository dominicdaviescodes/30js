# Day 1 split()

JavaScript String split() Method
Example
Split a string into an array of substrings:

```js
var str = "How are you doing today?";
var res = str.split(" ");
```
returns every word as an array, with no spaces

```js
Array(5)
0: "How"
1: "are"
2: "you"
3: "doing"
4: "today?"
length: 5

```
```js
var str = 'How are you doing today?';
var res = str.split('');

console.log(res);
```
Returns every single character as an array.

```js
(24) ["H", "o", "w", " ", "a", "r", "e", " ", "y", "o", "u", " ", "d", "o", "i", "n", "g", " ", "t", "o", "d", "a", "y", "?"]
```
if we pass in no argument

```js
var str = 'How are you doing today?';
var res = str.split();

console.log(res);

// returns our string as an array["How are you doing today?"]
```

### more examples.

```js
var str = 'Today was a productive day!';
var res = str.split(' ', 3);

console.log(res);

// returns ["Today", "was", "a"]
```
### nonsense! just returns returns our string as an array
We have no commas
```js
var str = 'Today was a productive day!';
var res = str.split(',');

console.log(res);

// ["Today was a productive day!"]
```
Lets split at the letter o
```js
var str = 'Today was a productive day!';
var res = str.split('o');

console.log(res);
// ["T", "day was a pr", "ductive day!"]
```

```js

```

```js

```

```js

```