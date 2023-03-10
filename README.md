# Question-1

```js
function arrayComposer(arr1, arr2) {
  const newArr1 = arr1.filter((value) => !arr2.includes(value));
  const newArr2 = arr2.filter(
    (value) => !arr1.includes(value) && !newArr1.includes(value)
  );

  return [...newArr1, ...newArr2];
}

const arr1 = prompt("Input for Array-1: ").split(" ");
const arr2 = prompt("Input for Array-2: ").split(" ");
console.log(arrayComposer(arr1, arr2));
```

# Question-2

```js
function arrayComposer(arr1, arr2) {
  const newArr1 = arr1.filter((value) => !arr2.includes(value));

  return newArr1;
}

const arr1 = prompt("Input for Array-1: ").split(" ");
const arr2 = prompt("Input for Array-2: ").split(" ");
console.log(arrayComposer(arr1, arr2));
```

# Question - 3

```js
function capitalizeEachWord(sentence) {
  const words = sentence.split(" ");
  const newWords = words.map((item) => item[0].toUpperCase() + item.slice(1));
  return newWords.join(" ");
}

const string = prompt("Input string: ");
console.log(capitalizeEachWord(string));
```

# Question - 4

```js
function calculateSum(string) {
  const arr = string.split(",");
  const sum = arr.reduce((acc, cur) => +acc + +cur, 0);
  return sum;
}

const string = prompt("Input string: ");
console.log(calculateSum(string));
```

# Question - 5

```js
function stringToArray(string) {
  return string.split(" ");
}

const s = prompt("Enter a text: ");
console.log(stringToArray(s));
```

# Question - 6

```js

```

# Question - 7

```js
function stringToChars(string) {
  return string.split("");
}

const string = prompt("Input string: ");
console.log(stringToChars(string));
```

# Question - 8

```js
function stringToASCII(string) {
  const arr = string.split("");
  return arr.map((item) => item.codePointAt(0));
}

const string = prompt("Input string: ");
console.log(stringToASCII(string));
```

# Question - 9

```js
function ASCIItoString(arr) {
  return arr.map((item) => String.fromCodePoint(item));
}

const arr = [104, 101, 108, 108, 111];
console.log(ASCIItoString(arr));
```

# Question - 10

```js

```

# Question - 11

```js
function calculateDistance(point1, point2) {
  const Xdiff = point1[0] - point2[0];
  const Ydiff = point1[1] - point2[1];

  return Math.sqrt(Math.pow(Xdiff, 2) + Math.pow(Ydiff, 2));
}

const point1 = prompt("X and Y coordinate for first point: ").split(" ");
const point2 = prompt("x and y coordinates for second point: ").split(" ");

console.log(calculateDistance(point1, point2));
```

# Question - 12

## Ans: Number of ways to make 1 dollar
