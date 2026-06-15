# Array Questions

## Q9 - Count Numbers Greater Than 50

```js
function countGreaterThan50(arr) {
  let count = 0;

  for (let num of arr) {
    if (num > 50) {
      count++;
    }
  }

  return count;
}
```

## Q10 - Get Even Numbers

```js
function getEvenNumbers(arr) {
  let result = [];

  for (let num of arr) {
    if (num % 2 === 0) {
      result.push(num);
    }
  }

  return result;
}
```
