# Words Splitter

## Usage
```js
let result = splitWords('Hello World. XD');
console.log(result); // [ 0, 6, 13 ]
console.log(result.length); // 3
console.log(cropText('Hello World. XD', 2, result)); // Hello World.
```
## Cases
```js
splitWords(' , , hi , ,');  // [ 5 ]
splitWords('中文-字XD'); // [ 0, 1, 3, 4 ]
```